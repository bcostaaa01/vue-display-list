<template>
<div>
<h2 v-for="name in names" :key="name">{{name}}</h2>
</div>
</template>

<script>
export default {
  name: "ListData",
  data () {
    return {
      names: ["Bruno", "Carlo", "Jake", "Jason"]
    }
  }
}
</script>