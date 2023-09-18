<template>
  <div class="container pt-5">
    <div class="row">
      <div class="col-3 m-1 header-bg">Header 1</div>
      <div class="col-2 m-1 header-bg">Header 2</div>
      <div class="col-2 m-1 header-bg">Header 3</div>
      <div class="col-2 m-1 header-bg">Header 4</div>
      <div class="col-1 m-1 header-bg">Header 5</div>
      <div class="col-1 m-1 header-bg">Header 6</div>
    </div>

    <div class="row">
      <div class="col-3 m-1 row-bg">
        <a
          href="https://medium.com/codingthesmartway-com-blog/introduction-to-bootstrap-4-flex-layout-flexbox-for-bootstrap-f85405ce5ebf"
          >Flex Tutorial</a
        >
      </div>
      <div class="col-2 m-1 row-bg"><a href="https://www.geeksforgeeks.org/bootstrap-grid-system/">Grid System</a></div>
      <div class="col-2 m-1 row-bg">Content 3</div>
      <div class="col-2 m-1 row-bg">Content 4</div>
      <div class="col-1 m-1 row-bg">Content 5</div>
      <div class="col-1 m-1 row-bg">Content 6</div>
    </div>
  </div>

  <div class="d-flex flex-row my-flex-container">
    <div class="p-2 my-flex-item">1</div>
    <div class="p-2 my-flex-item">2</div>
    <div class="p-2 my-flex-item">3</div>
  </div>

  <div class="d-flex flex-row-reverse my-flex-container">
    <div class="p-2 my-flex-item">1</div>
    <div class="p-2 my-flex-item">2</div>
    <div class="p-2 my-flex-item">3</div>
  </div>

  <div class="d-flex flex-row justify-content-center my-flex-container">
    <div class="p-2 my-flex-item">1</div>
    <div class="p-2 my-flex-item">2</div>
    <div class="p-2 my-flex-item">3</div>
  </div>

  <div class="d-flex flex-row justify-content-around my-flex-container">
    <div class="p-2 my-flex-item">1</div>
    <div class="p-2 my-flex-item">Content around</div>
    <div class="p-2 my-flex-item">3</div>
  </div>

  <div class="d-flex flex-row justify-content-between my-flex-container">
    <div class="p-2 my-flex-item">1</div>
    <div class="p-2 my-flex-item">Content between</div>
    <div class="p-2 my-flex-item">3</div>
  </div>

  <div class="d-flex flex-column my-flex-container-column">
    <div class="p-2 my-flex-item">Elrendezés</div>
    <div class="p-2 my-flex-item">oszloposan</div>
    <div class="p-2 my-flex-item">3</div>
  </div>

  <div class="d-flex flex-column-reverse my-flex-container-column">
    <div class="p-2 my-flex-item">1</div>
    <div class="p-2 my-flex-item">2</div>
    <div class="p-2 my-flex-item">Reverse order (oszlopos)</div>
  </div>

  <div class="d-flex flex-row align-items-center my-flex-container">
    <div class="p-2 my-flex-item">1</div>
    <div class="p-2 my-flex-item">Vertically center</div>
    <div class="p-2 my-flex-item">3</div>
  </div>

  <div class="d-flex flex-row my-flex-container">
    <div class="p-2 my-flex-item">Example</div>
    <div class="p-2 my-flex-item">of</div>
    <div class="p-2 my-flex-item">overflowing</div>
    <div class="p-2 my-flex-item">row...</div>
    <div class="p-2 my-flex-item">5</div>
    <div class="p-2 my-flex-item">6</div>
    <div class="p-2 my-flex-item">7</div>
    <div class="p-2 my-flex-item">8</div>
    <div class="p-2 my-flex-item">9</div>
    <div class="p-2 my-flex-item">10</div>
    <div class="p-2 my-flex-item">11</div>
    <div class="p-2 my-flex-item">12</div>
    <div class="p-2 my-flex-item">13</div>
    <div class="p-2 my-flex-item">14</div>
    <div class="p-2 my-flex-item">15</div>
    <div class="p-2 my-flex-item">16</div>
    <div class="p-2 my-flex-item">17</div>
    <div class="p-2 my-flex-item">18</div>
    <div class="p-2 my-flex-item">19</div>
    <div class="p-2 my-flex-item">20</div>
  </div>

  <div class="d-flex flex-row flex-wrap my-flex-container">
    <div class="p-2 my-flex-item">Overflow</div>
    <div class="p-2 my-flex-item">elkerülése</div>
    <div class="p-2 my-flex-item">új sorba</div>
    <div class="p-2 my-flex-item">tördeléssel</div>
    <div class="p-2 my-flex-item">5</div>
    <div class="p-2 my-flex-item">6</div>
    <div class="p-2 my-flex-item">7</div>
    <div class="p-2 my-flex-item">8</div>
    <div class="p-2 my-flex-item">9</div>
    <div class="p-2 my-flex-item">10</div>
    <div class="p-2 my-flex-item">11</div>
    <div class="p-2 my-flex-item">12</div>
    <div class="p-2 my-flex-item">13</div>
    <div class="p-2 my-flex-item">14</div>
    <div class="p-2 my-flex-item">15</div>
    <div class="p-2 my-flex-item">16</div>
    <div class="p-2 my-flex-item">17</div>
    <div class="p-2 my-flex-item">18</div>
    <div class="p-2 my-flex-item">19</div>
    <div class="p-2 my-flex-item">20</div>
  </div>
</template>

<style scoped>
.header-bg {
  background-color: lightgray;
}

.row-bg {
  background-color: aliceblue;
}

.my-flex-container {
  border: 2px solid green;
  height: 100px;
  margin-bottom: 20px;
}
.my-flex-container-column {
  border: 2px solid green;
  height: 200px;
  margin-bottom: 20px;
}
.my-flex-item {
  background-color: lightgrey;
  border: 1px dotted grey;
  height: 48px;
}
.my-flex-item-2 {
  background-color: lightgrey;
  border: 1px dotted grey;
  height: 96px;
}
</style>
