<template>
 
  <div class="mt-5">
      <h2>Login Page</h2>
 
      <form @submit.prevent="submitLoginForm">
         
        <input type="email" v-model="member.apiemail" placeholder="Email"   />
        <input type="password" v-model="member.apipassword" placeholder="Password"  /> 
        <button type="submit">LOGIN11 NOW</button>
      </form>
 </div>
</template>
  
<script setup>
  import { ref } from 'vue';
       
      const member = ref({ apiemail: '', apipassword:'' });
      const router = useRouter();

      const submitLoginForm = async () => {
 
    };
  
</script>