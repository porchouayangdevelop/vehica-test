<template>
  <div class="container">
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.15.4/css/all.css"
      integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm"
      crossorigin="anonymous"
    />
    <div class="features">
      <div
        class="
          features-header
          d-flex
          justify-content-between
          align-items-center
        "
      >
        <div class="left-feature">
          <h4 class="handy">Handy picked</h4>
          <h1 class="feature-text">Featured Listings</h1>
        </div>
        <div class="right-feature">
          <button class="btn_New">New</button>
          <button class="btn_used">Used</button>
        </div>
      </div>
      <div class="features-content">
        <div class="card card-feature1">
          <div class="feature-used">Featured</div>

          <img src="../images/bmw8.png" alt="pic" />
          <div class="card-body">
            <p class="card-text">BMW 8-series 2-door coupe gre</p>
            <h4 class="card-title">$62,000</h4>
            <hr class="hr" />
            <div class="action">
              <button class="btn_check">2021</button>
              <button class="btn-automatic">Automatic</button>
              <button class="btn-diesel">Diesel</button>
            </div>
          </div>
        </div>
        <div class="card card-feature2">
          <div class="feature-used">Featured</div>
          <img src="../images/Chevrolet.png" alt="pic" />
          <div class="card-body">
            <p class="card-text">Chevrolet Camaro 2-door convertible...</p>
            <h4 class="card-title">$40,000</h4>
            <hr class="hr" />
            <div class="action">
              <button class="btn_check">2021</button>
              <button class="btn-automatic">Automatic</button>
              <button class="btn-diesel">Diesel</button>
            </div>
          </div>
        </div>
        <div class="card card-feature4">
          <div class="feature-used">Featured</div>
          <img src="../images/Ferrari.png" alt="pic" />
          <div class="card-body">
            <p class="card-text">Ferrari LaFerrari 2-door coupe red</p>
            <h4 class="card-title">$810,000</h4>
            <hr class="hr" />
            <div class="action">
              <button class="btn_check">2021</button>
              <button class="btn-automatic">Automatic</button>
              <button class="btn-diesel">Diesel</button>
            </div>
          </div>
        </div>
        <div class="card card-feature4">
          <div class="feature-used">Featured</div>
          <img src="../images/Audi.png" alt="pic" />
          <div class="card-body">
            <p class="card-text">Audi A8 4-door sedan silver</p>
            <h4 class="card-title">$70,000</h4>
            <hr class="hr" />
            <div class="action">
              <button class="btn_check">2021</button>
              <button class="btn-automatic">Automatic</button>
              <button class="btn-diesel">Diesel</button>
            </div>
          </div>
        </div>
        <div class="card card-feature5">
          <div class="feature-used">Featured</div>
          <img src="../images/mrec.png" alt="pic" />
          <div class="card-body">
            <p class="card-text">Mercedes-Benz S-clcas 2-door coupe...</p>
            <h4 class="card-title">$76,000</h4>
            <hr class="hr" />
            <div class="action">
              <button class="btn_check">2021</button>
              <button class="btn-automatic">Automatic</button>
              <button class="btn-diesel">Diesel</button>
            </div>
          </div>
        </div>
      </div>
      <div
        class="feature-follow d-flex justify-content-between align-items-center"
      >
        <div class="left-follow">
          <h6 class="follow-text">Follow us:</h6>
          <button class="btn-social">
            <i class="fab fa-facebook-f"></i>
          </button>
          <button class="btn-social">
            <i class="fab fa-twitter"></i>
          </button>
          <button class="btn-social">
            <i class="fab fa-instagram"></i>
          </button>
        </div>
        <button class="btn-view">View New</button>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
};
</script>
<style scoped>
.container {
  width: 80%;
  margin: 10px auto;
}

.handy {
  color: #ff4605;
}
.feature-text {
  font-weight: 900;
}
.right-feature {
  display: flex;
  flex-wrap: nowrap;
}
.btn_New,
.btn_used {
  padding: 0.5rem 2rem;
  border-radius: 10px;
  border: none;
  outline: none;
  background: #eff0f1;
  margin: 0 0.2rem;
}
.btn_New:focus,
.btn_used:focus {
  border: 1px solid #ff4605;
  background: #fff0eb;
}
.left-follow {
  display: flex;
  align-items: center;
  grid-gap: 0.5rem;
}
.features-content {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr;
  grid-template-rows: repeat(1, 1fr);
  grid-gap: 1rem;
  margin: 5px 0;
}
.card {
  overflow: hidden;
  border-radius: 10px;
  position: relative;
}
img:hover {
  transition: transform 2s;
  transform: scale(1.1);
}
.feature-used {
  position: absolute;
  transform: rotate(320deg);
  text-align: center;
  width: 50%;
  top: 3%;
  left: -13%;
  color: #fff;
  background: #ff4605;
}
.card-body {
  background: #222732;
}
.card-feature1 {
  grid-column: 1/2;
  grid-row: 1/3;
}
.card-text {
  color: #eee;
}
.card-title {
  color: #fff;
}
.hr {
  background: rgb(92, 89, 89);
}
.btn_check {
  background: #ff4605;
  border-radius: 5px;
  border: none;
  outline: none;
  color: white;
  padding: 2px 10px;
  cursor: pointer;
}
.btn-automatic,
.btn-diesel {
  border: none;
  background: transparent;
  color: #eee;
  padding: 2px 10px;
  cursor: pointer;
}
.follow-text {
  color: #b3d2ff;
  margin-right: 1rem;
}
.btn-social {
  height: 40px;
  width: 40px;
  border-radius: 50px;
  border: none;
  outline: none;
}
.btn-view {
  border-radius: 10px;
  border: none;
  background: #ff4605;
  padding: 0.7rem 1.5rem;
  color: white;
  outline: none;
}
@media screen and (max-width: 590px) {
  .features-header {
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }
  .feature-follow {
    display: flex;
    flex-direction: column;
    margin-top: 1rem;
  }
  .btn-view {
    order: 1;
  }
  .left-follow {
    order: 2;
    margin-top: 1rem;
  }
  .features-content {
    display: flex;
    flex-direction: column;
  }
}
@media screen and (max-width: 950px) {
  .features-content {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(1, 1fr);
  }
  .card-feature1 {
    grid-column: 1/1;
    grid-row: 1/2;
  }
}
</style>