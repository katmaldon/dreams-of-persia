<template>
  <div class="card buy">
    <div class="card__text">
      <div class="card__title">{{ title }}</div>
      <div class="buy__cover">
        <img
          class="buy__img"
          src="@/assets/img/buybook.png"
          alt="Stack of books"
        />
      </div>
      <div class="buy__text">
        <p>
          We are thrilled to offer an exclusive discount to readers who purchase
          "Dreams of Persia" directly from the website of our publisher,
          <a
            href="https://store.bookbaby.com/book/dreams-of-persia"
            target="_blank"
            >BookBaby</a
          >, offering the most consistent availability of books as well as rapid
          shipping. <br /><br />Use code PERSEPOLIS to receive 25% off your
          order.<br />
        </p>
        <p>
          In addition, you can find our book at many great online retailers, as
          well as select local stores.
        </p>
      </div>
      <div class="buy__row">
        <div class="buy__column--bookbaby">
          <a
            href="https://store.bookbaby.com/book/dreams-of-persia"
            target="_blank"
          >
            <button class="buy__btn">BOOKBABY</button>
          </a>
        </div>
        <div class="buy__column--bookshop">
          <a
            href="https://bookshop.org/p/books/dreams-of-persia-a-collection-of-timeless-persian-sayings-and-proverbs-ab-sadeghi-nejad-md/20165448"
            target="_blank"
          >
            <button class="buy__btn">BOOKSHOP</button>
          </a>
        </div>
        <div class="buy__column--amazon">
          <a
            href="https://www.amazon.com/Dreams-Persia-Collection-Timeless-Proverbs/dp/1667878034"
            target="_blank"
          >
            <button class="buy__btn">AMAZON</button>
          </a>
        </div>
        <div class="buy__column--amazon">
          <a href="https://shop.harvard.com/book/9781667878034" target="_blank">
            <button class="buy__btn">HARVARD BOOKS</button>
          </a>
        </div>
        <!-- <div class="buy__column--harvard">
          <button class="buy__btn">HARVARD BOOKS</button>
          <a href="https://shop.harvard.com/book/9781667878034" target="_blank">
          </a>
        </div> -->
      </div>
    </div>
  </div>
</template>


<script>
export default {
  data() {
    return {
      title: "WHERE TO BUY",
    };
  },
};
</script>
