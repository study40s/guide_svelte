<script>
    import Header from "~/components/Header.svelte";
    import Footer from "~/components/Footer.svelte";
</script>

<Header />

<div class="container">

</div>

<Footer />

<style lang="scss">
.container {
    position: relative;
    max-width: 1120px;
    margin:0 auto;
    padding: 40px 0 0;
    @media #{$tablet} {
        padding: 40px 40px 0;
    }
    @media #{$mobile} {
        padding: 40px 20px 0;
    }
}
</style>