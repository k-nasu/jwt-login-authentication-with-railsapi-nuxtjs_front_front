<template>
  <v-btn
    text
    class="ml-2 font-weight-bold"
    color="$sub-color"
    to="/login"
  >
    {{ $injected.pageTitle('login' )}}
  </v-btn>
</template>

<script>
export default {

}
</script>