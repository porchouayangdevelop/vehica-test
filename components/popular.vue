<template>
  <div class="popular">
    <div class="container">
      <div class="Popular-make">
        <div class="p-header d-flex justify-content-between">
          <h1 class="header">Popular Makes</h1>
          <div class="d-flex flex-row flex-nowrap right-list">
            <button class="btn-list">
              <h5>Audi</h5>
              <p>14 Listings</p></button
            ><button class="btn-list">
              <h5>BMW</h5>
              <p>11 Listings</p></button
            ><button class="btn-list">
              <h5>Cadillac</h5>
              <p>13 Listings</p></button
            ><button class="btn-list">
              <h5>Ferrari</h5>
              <p>12 Listings</p>
            </button>
          </div>
        </div>
        <div class="popular-feature my-3">
          <b-row cols-sm="2" cols-md="3" cols-lg="4">
            <b-col>
              <div class="card card-list">
                <img src="../images/audiA4.png" alt="" />
                <div class="card-body">
                  <p class="card-text">Audi A4 4-door sedan</p>
                  <h4 class="card-title">$23,000</h4>
                  <hr />
                  <div class="action">
                    <button class="btn-check">2020</button>
                    <button class="btn-automatic">245,000 miles</button>
                    <button class="btn-manual">Manual</button>
                  </div>
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="card card-list">
                <img src="../images/Audi.png" alt="" />
                <div class="card-body">
                  <p class="card-text">Audi A8 4-door sedan silver</p>
                  <h4 class="card-title">$70,000</h4>
                  <hr />
                  <div class="action">
                    <button class="btn-check">2020</button>
                    <button class="btn-automatic">245,000 miles</button>
                    <button class="btn-manual">Manual</button>
                  </div>
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="card card-list">
                <img src="../images/audi5.png" alt="" />
                <div class="card-body">
                  <p class="card-text">Audi A8 4-door sedan blue</p>
                  <h4 class="card-title">$14,000</h4>
                  <hr />
                  <div class="action">
                    <button class="btn-check">2020</button>
                    <button class="btn-automatic">245,000 miles</button>
                    <button class="btn-manual">Manual</button>
                  </div>
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="card card-list">
                <img src="../images/AudiA8.png" alt="" />
                <div class="card-body">
                  <p class="card-text">Audi A8 4-door sedan silver</p>
                  <h4 class="card-title">$30,000</h4>
                  <hr />
                  <div class="action">
                    <button class="btn-check">2020</button>
                    <button class="btn-automatic">245,000 miles</button>
                    <button class="btn-manual">Manual</button>
                  </div>
                </div>
              </div>
            </b-col>
          </b-row>
        </div>
        <div class="page-navigate d-flex justify-content-between my-3">
          <div class="navigate">
            <button class="btn-prev">
              <i class="fas fa-chevron-left"></i>
            </button>
            <button class="btn-next">
              <i class="fas fa-chevron-right"></i>
            </button>
          </div>
          <button class="btn-view">View More</button>
        </div>
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
  margin: 0 auto;
  padding: 3rem 0;
}
.popular {
  background: #eff3fa;
}
.right-list {
  grid-gap: 0.3rem;
}
.btn-list {
  padding: 5px 15px;
  border: none;
  outline: none;
  background: #fff;
  border-radius: 10px;
  font-family: Ubuntu;
  line-height: 15px;
}
.btn-list:focus {
  background: #fff0eb;
  border: 1px solid #ff4605;
  color: #ff4605;
}
.card-list {
  cursor: pointer;
  border-radius: 10px;
  overflow: hidden;
  height: 100%;
}
img:hover {
  transition: transform 2s;
  transform: scale(1.1);
}
.card-body {
  background: #222732;
}
.card-text {
  color: #eee;
}
.card-title {
  color: #fff;
}
hr {
  background: rgb(95, 87, 87);
}

.btn-prev,
.btn-next {
  border: none;
  background: #fff;
  height: 40px;
  width: 40px;
  border-radius: 50px;
}
.btn-prev:hover,
.btn-next:hover {
  box-shadow: 2px 2px 5px #ffff, -2px -2px 5px #fff;
}
.btn-view {
  padding: 0.2rem 1rem;
  border-radius: 5px;
  border: none;
  background: #ff4605;
  color: #fff;
}
.btn-check {
  color: #fff;
  background: #ff4605;
  border-radius: 5px;
  border: none;
  padding: 2px 10px;
  cursor: pointer;
}
.btn-automatic,
.btn-manual {
  border: none;
  background: transparent;
  color: #fff;
}
@media screen and (max-width: 590px) {
  .p-header {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>
