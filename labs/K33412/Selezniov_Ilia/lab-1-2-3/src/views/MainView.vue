<template>
	<HeaderBlock />
	<MainBlock />
	<FooterBlock />
</template>

<script>
import { mapActions, mapState } from 'pinia'

// import useCardsStore from '@/stores/cards'

import HeaderBlock from '@/components/Header.vue'
import MainBlock from '@/components/Main.vue'
import FooterBlock from '@/components/Footer.vue'

export default{
	name: 'MainPage',

	components: {HeaderBlock,MainBlock, FooterBlock },

  // computed: {
  //   ...mapActions(useCardsStore, ['cards'])
  // },
  //
  // methods: {
  //   ...mapActions(useCardsStore, ['loadCards']),
  // },
}
</script>
