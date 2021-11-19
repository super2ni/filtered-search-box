<template>
  <div class="filtered-search-box">
    <input type="text" :value="value" @input="$emit($event)"/>
  </div>
</template>

<script>
export default {
  name: 'FilteredSearchBox',
  props: {
    value: {
      type:String,
      required:false,
      default(){
        return true;
      }
    }
  }
}
</script>
