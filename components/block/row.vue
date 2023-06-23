<template>
  <div class="container">
    <div class="row">ROW XXXXXXXXXXXXXXXX</div>
  </div>
</template>

<style>
.container {
  margin-left: auto;
  margin-right: auto;
}

.container.boxed {
  max-width: 1264px;
}

.row {
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 16px;
}

.row .row {
  margin-left: -8px;
  margin-right: -8px;
}

.row:after {
  content: '';
  display: table;
  clear: both;
}

@media (min-width: 600px) {
  .container {
    padding-left: 8px;
    padding-right: 8px;
  }
}

@media (min-width: 960px) {
  .container {
    padding-left: 16px;
    padding-right: 16px;
  }
}
</style>
