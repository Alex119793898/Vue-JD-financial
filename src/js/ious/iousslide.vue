<template>
  <article>
    <Slider :items="items" :cname="$style.slider"></Slider>
  </article>
</template>

<script>
import Slider from '../core/slide.vue';
export default {
  components: {
    Slider
  },
  data () {
    return {
      items: [
        {
          href: 'home',
          src:
            '//img12.360buyimg.com/jrpmobile/jfs/t8491/303/504628479/60643/100648de/59a94358N92475fca.jpg?width=750&height=320'
        },
        {
          href: 'home',
          src:
            '//img12.360buyimg.com/jrpmobile/jfs/t8437/321/1758527686/40952/f66d552f/59bf1f41N50d846f9.jpg?width=750&height=320'
        },
        {
          href: 'home',
          src:
            '//img12.360buyimg.com/jrpmobile/jfs/t8491/303/504628479/60643/100648de/59a94358N92475fca.jpg?width=750&height=320'
        }
      ]
    };
  }
};
</script>

<style lang="scss" module>
@import "../../css/element.scss";
.slider {
  margin-top: 3rem;
  img{
      width: 100%;
  }
}

</style>
