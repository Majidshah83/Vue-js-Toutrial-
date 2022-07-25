<template>
    <div>
    <table>
        <tr>
            <td>id</td>
            <td>name</td>
            <td>email</td>
        </tr>
         <tr v-for="user in users" :key="user.id">
            <td>1</td>
            <td>2</td>
            <td>3</td>
        </tr>
    </table>
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
   
        dataloop()
        {
            return {
               users:[
                   {id:1,name:'majid',email:'shahmajid508@gmail.com'},
                    {id:2,name:'ali',email:'ali@gmail.com'},
                     {id:3,name:'shah',email:'shah508@gmail.com'},
                ]
            }
        },
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