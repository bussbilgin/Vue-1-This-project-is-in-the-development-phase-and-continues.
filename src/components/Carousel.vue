<template>
  <div class="carousel-wrapper">
    <div class="container">
      <router-link to="/search" href="" class="carousel-item">
        <figure>
          <img src="/icon-meat.svg" alt="Meat Icon" />
        </figure>
        <span>meat</span>
      </router-link>
      <a href="" class="carousel-item">
        <figure>
          <img src="/icon-chicken.svg" alt="Chicken Icon" />
        </figure>
        <span>chicken</span>
      </a>
      <a href="" class="carousel-item">
        <figure>
          <img src="/icon-fish.svg" alt="Fish Icon" />
        </figure>
        <span>fish</span>
      </a>
      <a href="" class="carousel-item">
        <figure>
          <img src="/icon-sushi.svg" alt="Sushi Icon" />
        </figure>
        <span>sushi</span>
      </a>
      <a href="" class="carousel-item">
        <figure>
          <img src="/icon-salad.svg" alt="Salad Icon" />
        </figure>
        <span>salad</span>
      </a>
      <a href="" class="carousel-item">
        <figure>
          <img src="/icon-fast-food.svg" alt="Fast-Food Icon" />
        </figure>
        <span>fast-food</span>
      </a>
      <a href="" class="carousel-item">
        <figure>
          <img src="/icon-pizza.svg" alt="Pizza Icon" />
        </figure>
        <span>pizza</span>
      </a>
      <a href="" class="carousel-item">
        <figure>
          <img src="/icon-noddle.svg" alt="Noddle Icon" />
        </figure>
        <span>noddle</span>
      </a>
      <a href="" class="carousel-item">
        <figure>
          <img src="/icon-pasta.svg" alt="Pasta Icon" />
        </figure>
        <span>pasta</span>
      </a>
      <a href="" class="carousel-item">
        <figure>
          <img src="/icon-cake.svg" alt="Cake Icon" />
        </figure>
        <span>cake</span>
      </a>
      <a href="" class="carousel-item">
        <figure>
          <img src="/icon-ice-cream.svg" alt="Ice-Cream Icon" />
        </figure>
        <span>ice-cream</span>
      </a>
      <a href="" class="carousel-item">
        <figure>
          <img src="/icon-drink.svg" alt="Drink Icon" />
        </figure>
        <span>drink</span>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Carousel",
};
</script>

<style scoped lang="scss">
.carousel-wrapper {
  margin-bottom: 40px;

  .container {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;

    .carousel-item {
      margin-right: 15px;

      figure {
        width: 85px;
        height: 85px;
        border: 2px solid #000;
        border-radius: 100%;
        display: flex;
        align-items: center;
        justify-content: center;

        img {
          width: 50px;
        }
      }

      span {
        text-transform: uppercase;
        font-size: 15px;
        font-weight: bold;
        color: black;
        display: flex;
        justify-content: center;

        @media (max-width: 1024px) {
          font-size: 14px;
        }

        @media (max-width: 767px) {
          font-size: 13px;
        }
      }
    }
  }
}
</style>
