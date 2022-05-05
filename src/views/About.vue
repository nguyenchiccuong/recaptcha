<template>
  <div class="about">
    <vue-recaptcha
      @verify="onVerify"
      sitekey="6LeQu8cfAAAAAB7rJlm01UpiXM_kDDGof005gRuq"
      @error="errorMethod"
      ref='vueRecaptcha'
    ></vue-recaptcha>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import { VueRecaptcha } from "vue-recaptcha";

@Options({
  components: {
    VueRecaptcha,
  },
})
export default class About extends Vue {
$refs!: {
    vueRecaptcha: HTMLFormElement
  }

  onVerify(response: any): void {
    console.log("Verify: " + response);
    this.$refs.vueRecaptcha.reset()
  }

  errorMethod(): void {
    console.log("fail");
  }
}
</script>
