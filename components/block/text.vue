<script setup>
const props = defineProps({
  block: Object,
});
</script>

<template>
  <p class="text" :class="block.classes">
    {{ block.content }}
  </p>
</template>

<style>
.text {
  font-family: Inter, Roboto, 'Helvetica Neue', 'Arial Nova', 'Nimbus Sans',
    Arial, sans-serif;
}

/*--------------------------------------------------------------
## TYPOGRAPHY -> HEADLINE
--------------------------------------------------------------*/

.text-headline-l {
  font-weight: normal;
  font-size: 22px;
  line-height: 28px;
}

.text-headline-m {
  font-weight: normal;
  font-size: 20px;
  line-height: 24px;
}

.text-headline-s {
  font-weight: normal;
  font-size: 18px;
  line-height: 24px;
}

@media (min-width: 360px) {
  .text-headline-l {
    font-size: 32px;
    line-height: 40px;
  }

  .text-headline-m {
    font-size: 28px;
    line-height: 36px;
  }

  .text-headline-s {
    font-size: 24px;
    line-height: 32px;
  }
}

/*--------------------------------------------------------------
## TYPOGRAPHY -> DISPLAY
--------------------------------------------------------------*/

.text-display-l {
  font-weight: normal;
  font-size: 32px;
  line-height: 40px;
  letter-spacing: -0.25px;
  margin: 0;
}

.text-display-m {
  font-weight: normal;
  font-size: 28px;
  line-height: 36px;
  margin: 0;
}

.text-display-s {
  font-weight: normal;
  font-size: 22px;
  line-height: 32px;
  margin: 0;
}

@media (min-width: 360px) {
  .text-display-l {
    font-size: 40px;
    line-height: 52px;
  }

  .text-display-m {
    font-size: 32px;
    line-height: 40px;
  }

  .text-display-s {
    font-size: 28px;
    line-height: 36px;
  }
}

@media (min-width: 600px) {
  .text-display-l {
    font-size: 48px;
    line-height: 58px;
  }

  .text-display-m {
    font-size: 36px;
    line-height: 44px;
  }

  .text-display-s {
    font-size: 32px;
    line-height: 40px;
  }
}

@media (min-width: 1264px) {
  .text-display-l {
    font-size: 57px;
    line-height: 64px;
  }

  .text-display-m {
    font-size: 45px;
    line-height: 52px;
  }

  .text-display-s {
    font-size: 36px;
    line-height: 44px;
  }
}

@media (min-width: 1904px) {
  .text-display-l {
    font-size: 72px;
    line-height: 80px;
  }

  .text-display-m {
    font-size: 52px;
    line-height: 64px;
  }

  .text-display-s {
    font-size: 45px;
    line-height: 52px;
  }
}

/*--------------------------------------------------------------
## TYPOGRAPHY -> BODY
--------------------------------------------------------------*/

.text-body-l {
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.5px;
}

.text-body-m {
  font-size: 14px;
  line-height: 20px;
  letter-spacing: 0.25px;
}

.text-body-s {
  font-size: 12px;
  line-height: 16px;
  letter-spacing: 0.4px;
}

/*--------------------------------------------------------------
## TYPOGRAPHY -> LABEL
--------------------------------------------------------------*/

.text-label-l {
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
  letter-spacing: 0.1px;
}

.text-label-m {
  font-weight: 500;
  font-size: 12px;
  line-height: 16px;
  letter-spacing: 0.5px;
}

.text-label-s {
  font-weight: 500;
  font-size: 11px;
  line-height: 16px;
  letter-spacing: 0.5px;
}

/*--------------------------------------------------------------
## TYPOGRAPHY -> TITLE
--------------------------------------------------------------*/

.text-title-l {
  font-weight: 500;
  font-size: 22px;
  line-height: 28px;
  letter-spacing: 0;
}

.text-title-m {
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.1px;
}

.text-title-s {
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
  letter-spacing: 0.1px;
}

/*--------------------------------------------------------------
# FONT WEIGHTS
--------------------------------------------------------------*/

.bold {
  font-weight: 700;
}

.medium {
  font-weight: 500;
}

.normal {
  font-weight: 400;
}

.thin {
  font-weight: 100;
}
</style>
