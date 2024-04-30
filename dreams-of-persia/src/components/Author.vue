<template>
  <div class="card author">
    <div class="author__row">
      <img
        class="author__img"
        src="@/assets/img/AuthorIMG.jpg"
        alt="Portrait Ab Sadeghi-Nejad, MD"
      />
      <div class="card__text">
        <div class="card__title">{{ title }}</div>
        <p>
          Ab Sadeghi-Nejad. MD was born in Mashhad, Iran. He immigrated to the
          US in 1958, attending Beloit College and the University of Chicago
          Medical School. He completed a post-graduate residency in pediatrics
          at the University of Chicago, as well as fellowships in pediatric
          endocrinology at Tufts Medical Center in Boston and the University of
          California, San Francisco. <br />
          Ab returned to Tufts in 1970 and retired in 2019 after 50 years of
          dedicated service. He remains Professor of Pediatrics Emeritus at
          Tufts, as well as Chief Emeritus of Pediatric Endocrinology at Tufts
          Children’s Hospital (Boston Floating Hospital). In addition to
          lecturing extensively, both nationally and internationally, on
          pediatric endocrinology and medical ethics, he has published numerous
          articles and book chapters, which can be found on his
          <a
            href="https://en.wikipedia.org/wiki/Ab_Sadeghi-Nejad"
            target="_blank"
            >Wikipedia page</a
          >.<br /><br />
          Ab married Marion M. Marquardt, PhD in 1974. They have two children
          and four grandchildren. <br /><br />
          The couple lives in Chestnut Hill, MA.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "THE AUTHOR",
      //   card_imgURL: url("@/assets/img/Mosque.png"),
    };
  },
};
</script>
