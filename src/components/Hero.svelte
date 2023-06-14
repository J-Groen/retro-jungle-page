<section>
  <img src="/view_with_IE.gif" alt="" />
  <div class="text">
    <h1>Jungle is massive!</h1>
    <p>
      Jungle music captivates with its relentless energy, combining pulsating
      beats, intricate rhythms, and infectious basslines to create a sonic
      journey that is truly electrifying. Its fusion of diverse genres and
      seamless blending of old-school samples with futuristic soundscapes make
      it an unrivaled force in the world of electronic music.
    </p>
  </div>
</section>

<style>
  .text {
    background-color: rgba(0, 0, 0, 0.4);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  section {
    position: relative;
    background-image: url(../assets/hero.png);
    background-size: cover;
    background-position: center;
    height: 70vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  h1 {
    font-family: "Black_Wolf", sans-serif;
  }

  p {
    max-width: 600px;
    font-size: small;
  }

  img {
    position: absolute;
    top: 10px;
    right: 20px;
    scale: 1.5;
  }

  h1,
  p {
    color: white;
  }
</style>
