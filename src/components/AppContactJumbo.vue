<script>
export default {
    name:'AppContactJumbo',
}

</script>

<template>
    <section id="jumbotron">
        <div class="container-fluid p-5 text-center " >
            <h2 class="text-white position-absolute top-50 start-50 translate-middle fs-1" id="about-content">
                Contact            
            </h2>
        </div>
    </section>

</template>

<style scoped lang="scss">
@import '../assets/scss/partials/_variables.scss';

@keyframes fadeIn {
    0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

#about-content {
  animation: fadeIn 2s;
  letter-spacing: .15em;
}

#jumbotron .container-fluid {
    max-width: 100%;
    background-image: url(../img/banner-14@2x-scaled.jpg);
    background-size: cover;
    background-color: antiquewhite;
    background-color: #c4c3c3;
    background-blend-mode: multiply;
    height: 500px;
}

</style>
