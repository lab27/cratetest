<template lang="pug">
  .container
    nuxt-link(to="about").left About
    nuxt-link(to="contact").right contact
    h1 home page
    p Lorem ipsum dolor sit amet, in congue aliquando persequeris his, mea cu mazim repudiandae. Ad omnium diceret prodesset mea, munere audiam inciderint sit ea. An pri veri incorrupte, sit ne debitis atomorum. Nibh expetendis id duo, iisque feugait accusam eu nam, quo an aeterno vivendo. Munere nostro facilisis pri ne, alia numquam dolores sea in. Mea quaeque eligendi salutatus eu, nonumy putent senserit ea vis, quo eu minim recteque rationibus.

    p Eum no libris quidam dignissim. Ea quidam voluptatum nec. Te vix suscipit argumentum. Pri ne quodsi singulis praesent, suscipit tacimates senserit ut est.

    p Ut noster ponderum nec, delenit copiosae per ad. At primis epicuri scriptorem est, ullum quidam id his, quo inani decore delicatissimi id. Aliquam legimus ea nec. Ne per iudico petentium vituperatoribus.

    p Ius sumo explicari at. At qui movet viderer dolores, ex paulo persius albucius sit. Sit ea fuisset torquatos necessitatibus. Sed te error delenit, est no ridens ornatus suscipiantur, ne cum feugait epicurei persequeris.
    img(src="http://placehold.it/800x600")
    p Mel ut facilis albucius, qui ex adhuc fierent qualisque. Et sea altera molestiae, viderer recteque dissentiunt eu mei, ea eam dicam argumentum. Habeo semper patrioque sea ex. Ut vis soluta admodum, cu ius error nonumes singulis. Pri audiam aperiam vulputate ad, cibo melius et est, ignota vocibus an quo.

    p Detracto sententiae posidonium no has. Sea facer convenire prodesset ea, sit eu volutpat explicari, eruditi voluptaria adversarium eum et. Nec id propriae mediocrem repudiare, vim cetero dolorum dissentiunt cu. Mel eu sumo diam vitae, facer molestie signiferumque quo an, justo omnes cum an.

    p Ius ut illud essent perfecto, ius viris scriptorem id. Qui vocibus appetere constituam ut, autem eleifend ius et, has eu saperet repudiandae. Mei no putant volumus gloriatur. Te vel agam possit. Stet veri antiopam ut vis, usu cu iuvaret commune, nam tale duis no.

</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  transition: 'slide-fade',
  components: {
    Logo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  flex-flow: row wrap;
  font-size: 1rem;
  padding: 2rem 5rem;
  background: dodgerblue;
  color: white;
}

.left, .right {
  position: absolute;
}

.left {
  left: 1rem;
  top: 1rem;
}

.right {
  right: 1rem;
  top: 1rem;
}

p {
  font-size: 2rem;
}
.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
