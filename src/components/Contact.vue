<template>
  <article
    class="center w-pad-right w-pad-left w-pad-bottom round unfolded-border content-container"
  >
    <br />
    <br />
    <br />
    <div v-if="hideForm">
      <h3 class="txt-center">Tell me a little bit more about your project?</h3>
      <br />
      <form
        class="txt-left"
        name="submitContact"
        @submit.prevent="handleSubmit(onSubmit)"
      >
        <label for="message"
          >Share your ideas, goals and problems/solutions</label
        >
        <textarea name="message"></textarea>
        <label for="name">Name</label>
        <input type="text" name="name" />
        <label for="surname">Surname</label>
        <input type="text" name="surname" />
        <label for="email">Email</label>
        <input type="text" name="email" />
        <button
          @click="submitForm(), (showMsg = !showMsg), (hideForm = !hideForm)"
          class="right"
        >
          Send
        </button>
      </form>
    </div>
    <div v-if="!showMsg">
      <h3>Thanks for getting in touch, I'll get back to you shortly.</h3>
    </div>
  </article>
</template>

<script>
export default {
  data() {
    return {
      showMsg: true,
      hideForm: true,
    };
  },
  methods: {
    submitForm() {
      const scriptURL =
        "https://script.google.com/macros/s/AKfycbxkZUa3iPXA9z3y78MS-cdHVLUiJRoSri_rF0j1IJiOvwMyNwps/exec";
      const form = document.forms["submitContact"];

      fetch(scriptURL, { method: "POST", body: new FormData(form) })
        .then((response) => console.log("Success!", response))
        .catch((error) => console.error("Error!", error.message));
    },
  },
};
</script>

<style scoped lang="scss">
form {
  max-width: 768px;
  width: 97%;
}
textarea {
  resize: none;
}
</style>
