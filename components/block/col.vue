<template>
  <div class="col" :class="block.classes">COL</div>
</template>

<script setup>
const props = defineProps({
  block: Object,
});
</script>

<style>
.col {
  float: left;
  width: 100%;
  min-height: 1px;
  padding: 0 8px;
  margin-bottom: 16px;
}

.col.xs-1 {
  width: 25%;
}

.col.xs-2 {
  width: 50%;
}

.col.xs-3 {
  width: 75%;
}

.col.xs-4 {
  width: 100%;
}

@media (min-width: 600px) {
  .col.sm-1 {
    width: 12.5%;
  }

  .col.sm-2 {
    width: 25%;
  }

  .col.sm-3 {
    width: 37.5%;
  }

  .col.sm-4 {
    width: 50%;
  }

  .col.sm-5 {
    width: 62.5%;
  }

  .col.sm-6 {
    width: 75%;
  }

  .col.sm-7 {
    width: 87.5%;
  }

  .col.sm-8 {
    width: 100%;
  }
}

@media (min-width: 960px) {
  .col.md-1 {
    width: 8.3333333333%;
  }

  .col.md-2 {
    width: 16.6666666667%;
  }

  .col.md-3 {
    width: 25%;
  }

  .col.md-4 {
    width: 33.3333333333%;
  }

  .col.md-5 {
    width: 41.6666666667%;
  }

  .col.md-6 {
    width: 50%;
  }

  .col.md-7 {
    width: 58.3333333333%;
  }

  .col.md-8 {
    width: 66.6666666667%;
  }

  .col.md-9 {
    width: 75%;
  }

  .col.md-10 {
    width: 83.3333333333%;
  }

  .col.md-11 {
    width: 91.6666666667%;
  }

  .col.md-12 {
    width: 100%;
  }
}

@media (min-width: 1264px) {
  .col.lg-1 {
    width: 8.3333333333%;
  }

  .col.lg-2 {
    width: 16.6666666667%;
  }

  .col.lg-3 {
    width: 25%;
  }

  .col.lg-4 {
    width: 33.3333333333%;
  }

  .col.lg-5 {
    width: 41.6666666667%;
  }

  .col.lg-6 {
    width: 50%;
  }

  .col.lg-7 {
    width: 58.3333333333%;
  }

  .col.lg-8 {
    width: 66.6666666667%;
  }

  .col.lg-9 {
    width: 75%;
  }

  .col.lg-10 {
    width: 83.3333333333%;
  }

  .col.lg-11 {
    width: 91.6666666667%;
  }

  .col.lg-12 {
    width: 100%;
  }
}

@media (min-width: 1904px) {
  .col.xl-1 {
    width: 8.3333333333%;
  }

  .col.xl-2 {
    width: 16.6666666667%;
  }

  .col.xl-3 {
    width: 25%;
  }

  .col.xl-4 {
    width: 33.3333333333%;
  }

  .col.xl-5 {
    width: 41.6666666667%;
  }

  .col.xl-6 {
    width: 50%;
  }

  .col.xl-7 {
    width: 58.3333333333%;
  }

  .col.xl-8 {
    width: 66.6666666667%;
  }

  .col.xl-9 {
    width: 75%;
  }

  .col.xl-10 {
    width: 83.3333333333%;
  }

  .col.xl-11 {
    width: 91.6666666667%;
  }

  .col.xl-12 {
    width: 100%;
  }
}
</style>
