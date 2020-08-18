<template>
  <div>
    <card class="green-shadow center profile-display mb-3">
      <div class="block">
        <img src="../assets/profile.png" alt="Profile Photo" class="profile-photo" />
      </div>
      <div class="block">
        <span class="profile-title text-center">Felipe Augusto Silva Marques</span>
      </div>
      <div class="block">
        <span class="profile-subtitle">Desenvolvedor Back-End</span>
      </div>
      <div class="block">
        <span class="profile-info mt-3">
          <a href="mailto:felipe.augustosm@gmail.com">felipe.augustosm@gmail.com</a>
        </span>
      </div>
      <div class="block">
        <span class="profile-info mb-3">
          <a href="tel:+5531925433338">+55 (31) 99254-3338</a>
        </span>
      </div>
      <div class="block profile-icons">
        <div>
          <a href="https://github.com/felipemarques2020" target="_blank" class="center-grid">
            <i class="fa fa-github fa-2x"></i>
            <small>GitHub</small>
          </a>
        </div>
    </card>
  </div>
</template>

<style>
.fa-events-icons-ready {
  overflow: auto;
}
</style>

<script>
import Card from "../components/Card";

export default {
  components: { Card },
  beforeMount() {
    this.$parent.showLoading(false);
  }
};
</script>
