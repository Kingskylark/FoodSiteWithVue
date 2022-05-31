<template>
  <NavBar />
  <ContentSection />
  <FooterPart />
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue';
import FooterPart from '@/components/FooterPart.vue';
import ContentSection from '@/components/ContentSection.vue';


export default {
  name: 'HomeView',
  components: {
    NavBar,
    FooterPart,
    ContentSection,
    
}
}
</script>
