<template>
    <div id="wrapper" class="d-flex flex-column">
        <!-- <html prefix="og: http://ogp.me/ns#"> -->
        <header class="header-global">
            <starter-header></starter-header>
        </header>
        <main class="flex-fill position-relative">
           <nuxt />
        </main>
        <footer class="footer">
            <starter-footer></starter-footer>
        </footer>
    </div>
</template>

<script>
import StarterHeader from "~/components/argon-layout/starter/StarterHeader";
import StarterFooter from "~/components/argon-layout/starter/StarterFooter";

export default {
  components: {
    StarterHeader,
    StarterFooter
  }
};
</script>
<style>
body, #wrapper {
   min-height:100vh;
}
</style>
