<template>
  <footer style="margin: 5%;">
    <hr />
    <div class="row align-items-center justify-content-md-between">
      <div class="col-md-6">
        <div class="copyright">
          &copy; {{ year }}
          <a href="https://www.creative-tim.com" target="_blank" rel="noopener"
            >Creative Tim</a
          >
          &
          <a href="https://www.binarcode.com" target="_blank" rel="noopener"
            >Binar Code</a
          >
        </div>
      </div>
      <div class="col-md-6">
        <ul class="nav nav-footer justify-content-end">
          <li class="nav-item">
            <a
              href="https://www.creative-tim.com"
              class="nav-link"
              target="_blank"
              rel="noopener"
              >Creative Tim</a
            >
          </li>
          <li class="nav-item">
            <a
              href="https://www.creative-tim.com/presentation"
              class="nav-link"
              target="_blank"
              rel="noopener"
              >About Us</a
            >
          </li>
          <li class="nav-item">
            <a
              href="http://blog.creative-tim.com"
              class="nav-link"
              target="_blank"
              rel="noopener"
              >zzzz</a
            >
          </li>
          <li class="nav-item">
            <a
              href="https://github.com/creativetimofficial/argon-design-system/blob/master/LICENSE.md"
              class="nav-link"
              target="_blank"
              rel="noopener"
              >쿼카 기여웡</a
            >
          </li>
        </ul>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: "app-footer",
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style></style>
