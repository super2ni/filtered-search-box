<template>
  <div id="app">
    <FilteredSearchBox v-model="search"/>
  </div>
</template>

<script>
import FilteredSearchBox from './components/FilteredSearchBox.vue'

export default {
  name: 'App',
  components: {
    FilteredSearchBox
  },
  data() {
    return {
      search: ''
    }
  }
}
</script>
