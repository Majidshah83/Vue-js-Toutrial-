<template>
<div>
<h1>Helo majid</h1>
<h2>{{data}}</h2>
<h2>{{msg}}</h2>
</div>
</template>
<script>
export default {
  name:'HeloHome',
  props:{
    data:String,
    msg:String,
  }

}
</script>