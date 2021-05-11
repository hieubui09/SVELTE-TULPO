<script>
    	import { fade} from 'svelte/transition';
  let mobileMenu = false;
    function menuMobi() {
        mobileMenu = !mobileMenu;
    }
</script>

<header>
   <div class="container">
       <div class="logo">
        <a href="#">
            <img src="images/logo.png" alt="">
        </a>
       </div>
       <div class="menu__desktop">
           <div class="menu__item home"><a href="">Trang chủ</a></div>
           <div class="menu__item dv"><a href="">Dịch vụ</a></div>
           <div class="menu__item"><a href="">Quy trình</a></div>
           <div class="menu__item dv"><a href="">Sản xuất</a></div>
           <div class="menu__item"><a href="">Sự nghiệp</a></div>
           <div class="menu__item"><a href="">Tuyển dụng</a></div>
       </div>
       <div class="icon__menu" on:click={menuMobi}>
        {#if !mobileMenu}
           <img out:fade in:fade src="images/cate.png" alt="">
           {:else}
            <p out:fade in:fade >&#10539;</p>       
           {/if}
       </div>
       <div class="menu__mobi" class:menu__mobi--active={mobileMenu}>
        <ul>
            <li><a href="">Trang chủ</a></li>
            <li><a href="#news">Dịch vụ</a></li>
            <li><a href="#contact">Quy trình</a></li>
            <li><a href="#about">Sản xuất</a></li>
            <li><a href="#about">Sự nghiệp</a></li>
            <li><a href="#about">Tuyển dụng</a></li>
          </ul>
          
       </div>
   </div>
</header>

<style lang="scss">
    @import "../scss/header.scss";
</style>