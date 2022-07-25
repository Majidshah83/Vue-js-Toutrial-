<template>
    <div>
     <table>
        <tr>
        <td>id</td>
        <td>name</td>
        <td>email</td>
        </tr>
        <tr v-for="user in users" :key="user.id">
        <td>{{user.id}}</td>
        <td>{{user.name}}</td>
        <td>{{user.email}}</td>

        </tr>
     </table>
    </div>
</template>

<script>
export default {
    name:"ForLoop",
     data () {
      return {
        data_structures: [ 'Array', 'Linked-list', 'Stack',
        'Queue', 'Heap', 'Tree'],
        users:[

                {id:1,name:'majid',email:'shahmajid08@gmail.com'},
                 {id:2,name:'ali',email:'ali08@gmail.com'},
                  {id:3,name:'shah',email:'shah@gmail.com'},
                

            ]
      }
    }
 
};
</script>