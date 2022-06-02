<template>
  <footer>
      <div class="footer-wrapper">
        <div class="logo-footer">
          Logo
        </div>
        <div class="nav-footer">
          Navigation
        </div>
        <div class="contact-footer">
          Contact
        </div>
        <div class="social-media">
          Sosmed
        </div>
      </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style>
  footer {
    bottom: 0;
    padding-bottom: 1rem;
    margin-bottom: 2rem;
    border-bottom: 2px solid var(--color-border);
  }

  .footer-wrapper {
    display: flex;
    justify-content: space-between;
  }
  
</style>