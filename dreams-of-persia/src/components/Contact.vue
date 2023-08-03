<template>
  <div class="card contact">
    <div class="card__text">
      <div class="card__title">{{ title }}</div>
      <p>For all media inquiries, please use the form below to get in touch.</p>
    </div>
    <div class="contact__form">form</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "CONTACT",
    };
  },
};
</script>
