<template>
  <div>
    <div class="container mx-auto foo">
      <p @click="funC()" class="hover:bg-green-500">dfgkdfgld</p>
      <p @click="funC()" class="hover:bg-green-500">dfgkdfgld</p>
      <p @click="funC()" class="hover:bg-green-500">dfgkdfgld</p>
      <p @click="funC()" class="hover:bg-green-500">dfgkdfgld</p>
    </div>
  </div>
</template>

<script>
import { mapActions, mapGetters } from "vuex";
export default {
  name: "comCop",
  data() {
    return {};
  },
  computed: mapGetters(["getNumber"]),
  methods: {
    funC() {
      alert("chtoto");
    },
    // mapActions(['getClick'])
  },
};
</script>
