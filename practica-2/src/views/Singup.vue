<template>
    <div class="container">
      <img src="@/assets/logo.png" class="logoImg rounded d-block mx-auto" />
      <SingUp />
    </div>
</template>
  
<script>
  // @ is an alias to /src
  import SingUp from "@/components/singUp/singUp.vue";
    import SignUp from "@/components/singUp/singUp.vue";
  export default {
    name: "SingUp",
    components: {
      singUp,
    },
  };
</script>