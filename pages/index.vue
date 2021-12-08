<template>
  <!-- <b-container v-if="loading"></b-container> -->
  <div>
    <b-skeleton-wrapper :loading="loading">
      <template #loading>
        <b-skeleton width="85%" height="100%">
          <b-card>
            <b-row>sss</b-row>
            <b-row>sss</b-row>
            <b-row>sss</b-row>
            <b-row>sss</b-row>
          </b-card>
        </b-skeleton>
        <b-skeleton width="55%" height="100%"></b-skeleton>
        <b-skeleton width="70%" height="100%"></b-skeleton>
        <b-skeleton width="70%" height="100%"></b-skeleton>
        <b-skeleton width="70%" height="100%"></b-skeleton>
        <b-skeleton width="70%" height="100%"></b-skeleton>
      </template>

      <b-container class="container">
        <b-navbar type="dark" class="nav">
          <p class="title">Triplex</p>
          <b-img
            src="~/static/user.png"
            rounded="circle"
            alt="userImg"
            class="userImg"
          />
        </b-navbar>
        <b-row class="balanceWrapper mb-0">
          <!-- <b-col cols="10"> -->
          <b-card class="balanceCard">
            <b-row class="m-0">
              <b-col>
                <p class="m-0">เครดิตคงเหลือ</p>
                <p class="m-0">100.00 บาท</p>
              </b-col>
              <b-col>
                <p class="m-0">รายได้</p>
                <p class="m-0">00.00 บาท</p>
              </b-col>
            </b-row>
            <b-row class="m-0 mt-2 dw-btn">
              <b-col class="px-1"><b-button block>ฝาก</b-button></b-col>
              <b-col class="px-1"><b-button block>ถอน</b-button></b-col>
            </b-row>
          </b-card>
          <!-- </b-col> -->
        </b-row>
        <b-row class="my-0 menuTitle">
          <p class="m-0">เมนู</p>
        </b-row>
        <b-row class="menuWrapper my-0">
          <b-card class="menuCard">
            <b-row class="m-0 w-100">
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
            </b-row>
            <b-row class="m-0 w-100">
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
            </b-row>
            <b-row class="m-0 w-100">
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
            </b-row>
          </b-card>
        </b-row>
        <b-row class="my-0 menuTitle">
          <!-- <i class="las la-home"></i> -->
          <p class="m-0">เกมส์</p>
        </b-row>
        <b-row class="menuWrapper my-0">
          <b-card class="menuCard">
            <b-row class="m-0 w-100">
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
            </b-row>
            <b-row class="m-0 w-100">
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
            </b-row>
            <b-row class="m-0 w-100">
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
              <b-col class="p-1">
                <b-button block variant="outline-secondary">เมนู</b-button>
              </b-col>
            </b-row>
          </b-card>
        </b-row>
        <div class="footer">
          <ul class="footer-menu">
            <li>
              <a href="">
                <div class="menuGroup">
                  <i class="las la-home menu-icon"></i>
                  <p class="m-0">หน้าแรก</p>
                </div>
              </a>
            </li>
            <li>
              <a href="">
                <div class="menuGroup">
                  <i class="las la-users menu-icon"></i>
                  <p class="m-0">แนะนำ</p>
                </div>
              </a>
            </li>
            <li>
              <a href="">
                <div class="menuGroup">เข้าเล่น</div>
              </a>
            </li>
            <li>
              <a href="">
                <div class="menuGroup">
                  <i class="las la-headset menu-icon"></i>
                  <p class="m-0">ติดต่อ</p>
                </div>
              </a>
            </li>
            <li>
              <a href="">
                <div class="menuGroup">
                  <i class="lar la-user-circle menu-icon"></i>
                  <p class="m-0">ข้อมูลบัญชี</p>
                </div>
              </a>
            </li>
          </ul>
        </div>
      </b-container>
    </b-skeleton-wrapper>
  </div>
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
      loading: true,
    }
  },
  mounted() {
    this.$liffInit
      .then(() => {
        // eslint-disable-next-line no-undef
        if (liff.isLoggedIn()) {
          this.loading = !this.loading
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
    getUserProfile() {
      // eslint-disable-next-line no-undef
      liff
        .getProfile()
        .then((res) => {
          this.profile = res
        })
        .catch((err) => {
          console.log('err', err)
        })
    },
  },
}
</script>
<style scoped>
.container {
  padding: 0px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.nav {
  height: 72px;
  display: flex;
  justify-content: space-between;
  align-content: center;
}
.title {
  font-size: 24px;
  margin: 0px;
  padding: 0px;
}
.balanceWrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  margin: 16px 0px;
}
.balanceCard {
  display: flex;
  justify-content: center;
  width: 100%;
  margin: 0.5rem 1rem;
}
.card-body {
  padding: 10px;
}
.balance {
  font-size: 16px;
}
.playBalance {
  font-size: 12px;
}
.dw-btn {
  display: flex;
}
.menuWrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  margin: 16px 0px;
}
.menuCard {
  display: flex;
  justify-content: center;
  width: 100%;
  margin: 0.5rem 1rem;
}
.menuTitle {
  margin: 0.5rem 1rem;
}
.userImg {
  width: 50px;
  height: 50px;
}
.footer {
  position: fixed;
  z-index: 8888;
  bottom: 0;
  height: 60px;
  width: 100%;
  margin: 0;
  padding: 0;
  text-align: center;
}
div.footer ul.footer-menu {
  list-style: none;
  display: inline-flex;
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
  background: #000;
}
div.footer ul.footer-menu li {
  width: 20%;
}
.menuGroup {
  font-size: 13px;
  color: #fff;
}
.menu-icon {
  font-size: 20px;
}
li {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
