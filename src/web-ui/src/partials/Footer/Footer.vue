<template>
  <footer>
    <div class="container justify-content-center d-flex align-items-center">
      <div class="rds">Retail Demo Store</div>
      <div class="separator mx-2" aria-hidden></div>
      <img src="/powered-by-logo.svg" alt="powered by AWS" class="img" />
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
};
</script>

<style scoped>
.rds {
  font-weight: 500;
}

.separator {
  height: 30px;
  width: 2px;
  background: var(--grey-600);
}

.img {
  /* fine-tuning to match other copy in footer */
  margin-top: 10px;
  height: 30px;
}

@media (min-width: 576px) {
  .rds {
    font-size: 1.4rem;
  }

  .separator {
    height: 40px;
  }

  .img {
    margin-top: 14px;
    height: 40px;
  }
}
</style>
