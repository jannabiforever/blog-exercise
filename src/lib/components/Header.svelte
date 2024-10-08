<script lang="ts">
</script>

<div class="nav-bar">
  <div class="nav-bar__logo">
    <a href="/">
      <img src="/images/logo.svg" alt="Logo" />
    </a>
  </div>
  <div class="nav-bar__menu">
    <a href="/about">About</a>
    <a href="/thoughts">Thoughts</a>
  </div>
</div>


<style>
  .nav-bar {
    display: flex;
    justify-content: space-between;
    align-items: center;

    background-color: #f8f8f8;
    margin: 0;
  }

  .nav-bar__logo img{
    width: 3rem;
    margin: 1rem;
  }

  .nav-bar__menu {
    display: flex;
    gap: 1rem;
    margin-right: 1rem;
  }

  .nav-bar__menu a {
    text-decoration: none;
    color: #333;
    font-weight: 600;
    padding: 0.5rem 1rem;
    border-radius: 0.5rem;
    transition: background-color 0.3s ease, color 0.3s ease;
  }

  .nav-bar__menu a:hover {
    background-color: #333;
    color: #fff;
  }

  .nav-bar__menu a:active {
    background-color: #555;
  }
</style>