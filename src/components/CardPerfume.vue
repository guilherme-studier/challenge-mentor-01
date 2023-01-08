<template>
  <div class="card">
      <img src="../assets/image-product-desktop.jpg" alt="">
      <div class="card__content">
        <div>
          <div class="card__content__title">
            <h3>PERFUME</h3> 
          </div>
          <div class="card__content__name">
            <h1>Gabrielle Essence Eau De Parfum</h1>
          </div>
          <div class="card__content__description">
            <p>A floral, solar and voluptuous interpretation composed by Olivier Polge, Perfumer-Creator for the House of CHANEL.</p>
          </div>
          <div class="card__content__price">
            <h2>$149.99</h2>
            <p>$169.99</p>
          </div>
          <div class="card__content__btn">
            <button>Add to Cart</button>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
  .card {
    display: flex;
    width: 37.5rem;
    height: 26rem;
    overflow: hidden;
    margin: 3rem;
    
    border-radius: 10px;
    background: var(--white);
  }

  .card img {
    width: 50%;
    height: 100%;

    object-fit: cover;
    border-top-left-radius: 10px;
    border-bottom-left-radius: 10px;
  }

  .card > .card__content {
    display: grid;
    align-items: center;
    padding: 2rem;

    width: 50%;
    height: 100%;
  }

  .card > .card__content div {
    padding-bottom: 1rem;
  }

  .card > .card__content .card__content__title h3 {
    color: var(--dark-grayish-blue);
  }
  .card > .card__content .card__content__name h1 {
    font-size: 2rem;
    font-family: 'Fraunces', serif;
  }

  .card > .card__content .card__content__description p {
    font-size: 0.875rem;
    color: var(--dark-grayish-blue);
  }

  .card > .card__content .card__content__price {
    display: flex;
  }

  .card > .card__content .card__content__price h2 {
    font-size: 2rem;
    font-family: 'Fraunces', serif;
    color: var(--dark-cyan);
  }

  .card > .card__content .card__content__price p {
      font-size: 0.7rem;
      font-family: 'Fraunces', serif;
      color: var(--dark-grayish-blue);
      display: flex;
      align-content: center;
      flex-wrap: wrap;
      padding: 0.5rem 0.5rem 0.5rem 1rem;
      text-decoration: line-through;
  }

  .card > .card__content .card__content__btn button {
    background-color: var(--dark-cyan);
    color: var(--white);
    border-radius: 5px;
    border: none;
    padding: 1rem;
    cursor: pointer;
    width: 100%;

    transition: 0.2s;
  }

  .card > .card__content .card__content__btn button:hover {
    background-color: var(--very-dark-blue);
  }

  @media screen and (max-width: 720px) {
    .card {
      display: block;
      width: 24rem;
      height: 43rem;
    }

    .card img {
      width: 100%;
      height: 50%;
      border-top-left-radius: 10px;
      border-top-right-radius: 10px;
      border-bottom-left-radius: 0px;
    }

    .card > .card__content {
      width: 100%;
      height: 50%;
      padding: 1.5rem;
    }
  }

</style>