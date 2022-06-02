<template>
  <header>

    <div class="nav-wrapper">
      
      <img
        alt="Vue logo"
        class="logo"
        src="@/assets/logo.svg"
        width="56 "
        height="56"
      />
      <h1>Logo</h1>
      <nav>
        <RouterLink to="/">Beranda</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>
</template>

<style scoped>
  header { 
    position: absolute;
    width: 100%;
    line-height: 1.5;
    z-index: 99;
  }

  .logo {
    display: block;
    margin: 0 auto 2rem;
  }

  a,
  .green {
    text-decoration: none;
    color: hsla(160, 100%, 37%, 1);
    transition: 0.4s;
  }

  @media (hover: hover) {
    a:hover {
      background-color: hsla(160, 100%, 37%, 0.2);
    }
  }

  nav {
    width: 100%;
    font-size: 12px;
    text-align: center;
  }

  nav a.router-link-exact-active {
    color: var(--color-text);
    padding-bottom: 5px;
    border-bottom: 2px solid var(--color-border);
  }

  nav a.router-link-exact-active:hover {
    background-color: transparent;
  }

  nav a {
    display: inline-block;
    padding: 0 1rem;
  }

  nav a:first-of-type {
    border: 0;
  }


  @media (min-width: 1024px) {
    header {
      display: flex;
      padding-top: 1rem;
      display: block;
    }

    header .nav-wrapper {
      position: relative;
      display: flex;
    }

    .logo {
      margin: 0 2rem 0 0;
    }

    nav {
      text-align: right;
      font-size: 1rem;

      padding: 1rem 0;
    }
  }
</style>