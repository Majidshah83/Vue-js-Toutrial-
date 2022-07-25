<template>
    <div>
   <h1>helo</h1>
   <button v-on:click="helo">Helo Button</button>
   <button v-on:mouseover="helo2('i am majid shah')">click me </button>
   <h1 v-if="show">condition true</h1>
   <h1 v-else>condition false</h1>
   <button v-on:click="display">toggle button</button>
    </div>
</template>

<script>
export default {
    name:'OnclickEvents',
    data()
        {
            return{show:true}
        },
    methods:{
        helo()
        {
            
            alert('majid shah')
        },
        helo2(data)
        {
            alert(data)
        },
        display()
        {
           this.show=!this.show;
        }
        

    }
    
}
</script>