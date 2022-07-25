<template>
    <div>
   <h1>helo</h1>
   <button v-on:click="helo">Helo Button</button>
   <button v-on:mouseover="helo2('i am majid shah')">click me </button>
    </div>
</template>

<script>
export default {
    name:'OnclickEvents',
    methods:{
        helo()
        {
            
            alert('majid shah')
        },
        helo2(data)
        {
            alert(data)
        }
    }
    
}
</script>