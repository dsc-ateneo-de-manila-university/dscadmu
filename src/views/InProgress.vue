<template>
  <section id="wip" class="grey-bg">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-12 col-md-6 left">
          <h4>Oops...</h4>
          <h1>Still working on it</h1>
          <p class="feature-text">
            The page is not yet done but don't worry. Maybe on your next visit,
            the page is already up and working!
          </p>
        </div>
        <div class="col-12 col-md-6 right">
          <img src="../assets/images/wip.svg" alt="DSC mascot wrench" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  mounted() {
    window.scrollTo(0, 0);
  }
};
</script>

<style scoped>
#wip {
  margin-top: 60px;
  width: 100%;
}

#wip h1 {
  margin-bottom: 16px;
}

#wip h4 {
  color: #fbbc04;
  margin-top: 96px;
  margin-bottom: 24px;
}

#wip .left {
  max-width: 410px;
}

#wip .right {
  position: relative;
  top: 60px;
  max-width: 400px;
}

#wip img {
  width: 100%;
}

@media screen and (max-width: 767px) {
  #wip h4 {
    margin-top: 24px;
  }
}
</style>
