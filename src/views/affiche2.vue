<template>
  <div>
    <div class="container">
      <div class="card-deo">
        <video autoplay loop muted>
          <source src="../assets/jolixi-deo-1.webm" type="video/webm" />
        </video>
      </div>
      <div class="card-deo">
        <video autoplay loop muted>
          <source src="../assets/jolixi-deo-2.webm" type="video/webm" />
        </video>
      </div>
      <div class="card-deo">
        <video autoplay loop muted>
          <source src="../assets/jolixi-deo-1.webm" type="video/webm" />
        </video>
      </div>
      <div class="card-deo">
        <video autoplay loop muted>
          <source src="../assets/jolixi-deo-2.webm" type="video/webm" />
        </video>
      </div>
      <div class="card-deo">
        <video autoplay loop muted>
          <source src="../assets/jolixi-deo-1.webm" type="video/webm" />
        </video>
      </div>
      <div class="card-deo">
        <video autoplay loop muted>
          <source src="../assets/jolixi-deo-2.webm" type="video/webm" />
        </video>
      </div>
      <div class="card-deo">
        <video autoplay loop muted>
          <source src="../assets/jolixi-deo-1.webm" type="video/webm" />
        </video>
      </div>
      <div class="card-deo">
        <video autoplay loop muted>
          <source src="../assets/jolixi-deo-2.webm" type="video/webm" />
        </video>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
  gap: 10px;
  margin: 25px 0;
}

.card-deo {
  height: 300px;
}

.card-deo video {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>
