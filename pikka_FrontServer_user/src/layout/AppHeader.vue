<template>
  <header class="header-global">
    <base-nav
      transparent
      type=""
      effect="light"
      expand
      style="background-image: linear-gradient(-225deg, #B7F8DB 0%, #50A7C2 100%);  box-shadow: 0 3px 6px rgba(0,0,0,0.16), 0 3px 6px rgba(0,0,0,0.23);"
    >
      <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
        <img src="../../public/img/brand/wejob.png" alt="logo" />
      </router-link>


      <div>

        <router-link to="/job" class="nav-link">취업</router-link>

      </div>
      
      <router-link to="/certification" class="nav-link">자격증</router-link>
      <router-link to="/post" class="nav-link">게시판</router-link>

    

      <base-dropdown tag="li" class="nav-item">
        <a
          slot="title"
          href="#"
          class="nav-link dropdown-toggle"
          data-toggle="dropdown"
          role="button"
        >
          <img
            src="../../public/img/icons/common/heander-icon.svg"
            alt="header-icon"
            style="width: 30px; height: 30px;"
          />
        </a>
        <router-link to="/write" class="dropdown-item">글쓰기</router-link>
        <router-link to="/inquiry" class="dropdown-item">문의하기</router-link>
        <router-link to="/history" class="dropdown-item">문의내역</router-link>
      </base-dropdown>

      <!-- <base-dropdown tag="li" class="nav-item">
        <a
          slot="title"
          href="#"
          class="nav-link"
          data-toggle="dropdown"
          role="button"
        >
          <span class="nav-link-inner--text"></span>
        </a>

      
        
        
        <router-link to="/register" class="dropdown-item">??관리자??로그인??</router-link>
      </base-dropdown> -->

      <ul class="navbar-nav align-items-lg-center ml-lg-auto">
        <li class="nav-item">
          <a
            class="nav-link nav-link-icon"
            href="https://www.facebook.com/creativetim"
            target="_blank"
            rel="noopener"
            data-toggle="tooltip"
            title="Like us on Facebook"
          >
            <i class="fa fa-facebook-square"></i>
            <span class="nav-link-inner--text d-lg-none"></span>
          </a>
        </li>
        <li class="nav-item">
          <a
            class="nav-link nav-link-icon"
            href="https://www.instagram.com/creativetimofficial"
            target="_blank"
            rel="noopener"
            data-toggle="tooltip"
            title="Follow us on Instagram"
          >
            <i class="fa fa-instagram"></i>
            <span class="nav-link-inner--text d-lg-none"></span>
          </a>
        </li>
        <li class="nav-item">
          <a
            class="nav-link nav-link-icon"
            href="https://twitter.com/creativetim"
            target="_blank"
            rel="noopener"
            data-toggle="tooltip"
            title="Follow us on Twitter"
          >
            <i class="fa fa-twitter-square"></i>
            <span class="nav-link-inner--text d-lg-none"></span>
          </a>
        </li>
        <li class="nav-item">
          <a
            class="nav-link nav-link-icon"
            href="https://github.com/creativetimofficial/vue-argon-design-system"
            target="_blank"
            rel="noopener"
            data-toggle="tooltip"
            title="Star us on Github"
          >
            <i class="fa fa-github"></i>
            <span class="nav-link-inner--text d-lg-none"></span>
          </a>
        </li>
      </ul>
    </base-nav>
  </header>
</template>

<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";

export default {
  components: {
    BaseNav,
    BaseDropdown,
  },
};
</script>
<style></style>
