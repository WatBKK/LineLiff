<template>
  <Tutorial />
</template>

<script>
import packageJson from '../package.json'
export default {
  data() {
    return {
      version: packageJson.version,
      sdkVersion: '',
      profile: '',
      liffError: '',
    }
  },
  mounted() {
    this.$liffInit
      .then(() => {
        // eslint-disable-next-line no-undef
        if (liff.isLoggedIn()) {
          this.getUserProfile()
        } else {
          // eslint-disable-next-line no-undef
          liff.login()
        }
      })
      .catch((error) => {
        this.liffError = error
      })
  },
  methods: {
    getUserProfile() {},
  },
}
</script>
