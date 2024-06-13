<script>
import AppContactJumbo from '../components/AppContactJumbo.vue'
import AppContactForm from'../components/AppContactForm.vue';
import AppTestimonial from '../components/AppTestimonial.vue';
import AppNewsLetter from '../components/AppNewsLetter.vue';
import AppStaff from '../components/AppStaff.vue';

export default{
    name: 'AppContact',
    components: {
      AppContactJumbo,
      AppContactForm,
      AppTestimonial,
      AppNewsLetter,
      AppStaff,   
    }
}
</script>

<template>

    <!----Inizio Sezione Jumbotron-->
    <AppContactJumbo />
    <!----Fine Sezione Jumbotron-->
    
    <!----Inizio Sezione Forms-->
    <AppContactForm />
    <!----Fine Sezione Form-->

    <!----Inizio Sezione Testimonial-->
        <AppTestimonial :limit="3"  />
    <!----Fine Sezione Testimonial-->

    <!----Inizio Sezione NewsLetter-->
    <AppNewsLetter />
    <!----Fine Sezione NewsLetter-->

    <!----Inizio Sezione Staff-->
    <AppStaff />
    <!----Fine Sezione Staff-->

</template>

<style scoped lang="scss">

</style>