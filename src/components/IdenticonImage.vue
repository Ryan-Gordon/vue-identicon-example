<template>
  <div>
    <Identicon
      size="128"
      value='5F1aGzHi5uJkRdegzBNj4fhG81ZtrWS79TrErTa7qL7ih4ik'
      theme='beachball'
    />
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';
import Identicon from '@vue-polkadot/vue-identicon';

@Component({
  components: {
    Identicon
  }
})
export default class IdenticonImage extends Vue {
}
</script>