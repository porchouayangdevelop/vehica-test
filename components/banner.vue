<template>
  <div class="banner-bg">
    <div class="banner-container">
      <h1 class="text-banner">
        Find Your
        <span class="text-span">Perfect</span>
        Car
      </h1>
      <div class="list-banner">
        <button class="btn_list">All</button>
        <button class="btn_list">New</button>
        <button class="btn_list">Used</button>
      </div>
      <div class="box-search">
        <select name="" id="" class="All-Model">
          <option value="">All Makes</option>
        </select>

        <select name="" id="" class="All-Make">
          <option value="">All Models</option>
        </select>

        <select name="" id="" class="max-price">
          <option value="">Max price</option>
        </select>

        <button class="btn-search">
          <i class="fas fa-search"></i>
        </button>
      </div>
      <div class="model">
        <div class="img1">
          <img
            src="../images/hatchback-car-variant-side-view-silhouette.png"
            alt=""
          />
          <p>Sedan</p>
        </div>

        <div class="img2">
          <img
            src="../images/hatchback-car-variant-side-view-silhouette.png"
            alt=""
          />
          <p>Coupe</p>
        </div>

        <div class="img3">
          <img
            src="../images/hatchback-car-variant-side-view-silhouette.png"
            alt=""
          />
          <p>SUV</p>
        </div>

        <div class="img4">
          <img
            src="../images/hatchback-car-variant-side-view-silhouette.png"
            alt=""
          />
          <p>Hatchback</p>
        </div>

        <div class="img5">
          <img
            src="../images/hatchback-car-variant-side-view-silhouette.png"
            alt=""
          />
          <p>Convertible</p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style scoped>
.banner-bg {
  height: 800px;
  background: url("../images/bg-1920-new.jpg") no-repeat;
  background-size: cover;
}
.banner-container {
  height: 800px;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.text-banner {
  color: #fff;
  font-weight: 900;
  font-size: 50px;
}
.text-span {
  font-weight: 900;
  font-size: 50px;
}
.btn_list {
  padding: 2px 4px;
  background: transparent;
  color: #fff;
  border: none;
  margin: 1.3rem 1.2rem;
  font-size: 18px;
}
.btn_list:focus {
  color: #ff4605;
}
.box-search {
  padding: 20px;
  background: #fff;
  border-radius: 20px;
  box-shadow: 0px 10px 1px rgb(139, 141, 142);
  display: flex;
  grid-gap: 7px;
  font-family: Ubuntu;
  width: 50%;
}
.All-Make,
.All-Model,
.max-price {
  padding: 10px 2rem;
  border-radius: 5px;
  border: 1px solid #eee;
  outline: none;
  cursor: pointer;
  width: 100%;
}
.All-Make:focus,
.All-Model:focus,
.max-price:focus {
  border: 1px solid #ff4605;
}
option:focus-visible {
  background: none;
}
.btn-search {
  padding: 10px 15px;
  background: #ff4605;
  border-radius: 5px;
  border: none;
  outline: none;
  color: #fff;
}
.model {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  grid-template-rows: repeat(1, 1fr);
  grid-gap: 2rem;
  margin: 4rem auto;
  font-family: "Ubuntu";
}
.img1,
.img2,
.img3,
.img4,
.img5 {
  width: 80px;
  height: 80px;
  color: white;
  border: 2px solid #fff;
  border-radius: 50%;
  padding: 10px;
  display: flex;
  align-items: center;
  flex-direction: column;
  grid-gap: 20px;
  cursor: pointer;
}
.img1 > img,
.img2 > img,
.img3 > img,
.img4 > img,
.img5 > img {
  height: 100%;
  width: 100%;
}
@media screen and (max-width: 590px) {
  .box-search {
    width: 95%;
  }
  .banner-container {
    padding-top: 7rem;
  }
  .text-banner {
    font-size: 30px;
  }
  .text-span {
    font-size: 30px;
    color: #ff4605;
  }
  .model {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(1fr, 1fr);
  }
  .img4 {
    grid-column: 2/3;
    margin-left: -50px;
  }
  .img5 {
    margin-left: -50px;
    grid-column: 3/4;
  }
}
@media screen and (max-width: 840px) {
  .box-search {
    display: flex;
    flex-direction: column;
    /* width: 60%; */
  }
  .All-Make,
  .All-Model,
  .max-price {
    width: auto;
  }
  .btn-search::before {
    content: "Search";
    margin-right: 10px;
  }
}
</style>