<template>
  <Panel :class="$style.panel">
    <div :class="$style.content">
      <img
        src="//img12.360buyimg.com/jrpmobile/jfs/t10876/23/2566835181/40527/d7d27c08/59f97d68Ne53fda5b.png?width=1080&height=240"
        alt
      />
    </div>
  </Panel>
</template>

<script>
import Panel from '../core/panel'
export default {
  components: {
    Panel
  }
};
</script>

<style lang="scss" module>
    .panel{
        >h4{
            display: none;
        }
        .content{
            img {
                width: 100%;
                // height: 3.55rem;
            }
        }
    }
</style>
