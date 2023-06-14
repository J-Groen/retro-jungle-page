<section class="artists">
  <h2>Artists</h2>

  <div class="container">
    <div class="peshay">
      <a
        href="https://www.discogs.com/artist/278-Peshay"
        target="_blank"
        rel="noopener noreferrer"
        ><img src="/artists/peshay.png" class="image" /></a
      >
      <div class="about">
        <h3>Peshay</h3>
        <p>
          Peshay is a British drum and bass DJ and record producer. He has been
          active since 1992, when he and fellow DJ, Roger Johnson, formed
          Hyper-On Experience, releasing their first record in 1992 on the
          Moving Shadow label.
        </p>
      </div>
    </div>
    <div class="sawteeth">
      <a
        href="https://www.discogs.com/artist/11397065-Sawteeth"
        target="_blank"
        rel="noopener noreferrer"
        ><img src="/artists/sawteeth.png" class="image" /></a
      >
      <div class="about">
        <h3>Sawteeth</h3>
        <p>
          Sawteeth is a drum and bass producer from the UK. He has been
          producing music since 2018 and has released on labels such as
          Repertoire, Rua Sound, and Western Lore.
        </p>
      </div>
    </div>
    <div class="bailey">
      <a
        href="https://www.discogs.com/artist/18690-DJ-Bailey"
        target="_blank"
        rel="noopener noreferrer"
        ><img src="/artists/bailey.png" class="image" /></a
      >
      <div class="about">
        <h3>DJ Bailey</h3>
        <p>
          Bailey is a British drum and bass DJ and record producer. He has been
          a regular DJ on BBC Radio 1Xtra since 2002. He was a member of the
          drum and bass group, Inta Warriors, with Shy FX.
        </p>
      </div>
    </div>
    <div class="M-beat">
      <a
        href="https://www.discogs.com/artist/17291-M-Beat"
        target="_blank"
        rel="noopener noreferrer"
        ><img src="/artists/mbeat.png" class="image" /></a
      >
      <div class="about">
        <h3>M-Beat</h3>
        <p>
          M-Beat is a British DJ and record producer from London. He is best
          known for his collaborations with General Levy, including "Incredible"
          and "Incredible (Remix)", and his remix of Renk Records' "Something
          Out of Nothing", which reached number 29 in the UK Singles Chart in
          July 1994.
        </p>
      </div>
    </div>
  </div>
</section>

<style>
  .container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    justify-items: center;
    align-content: start; /* Align rows to the top */
    grid-auto-rows: min-content; /* Set row height to fit content */
  }

  .peshay,
  .sawteeth,
  .bailey,
  .M-beat {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    color: #acacac;
  }

  .about {
    margin-top: auto;
    flex-grow: 1;
  }

  img {
    width: 100%;
    height: auto;
    object-fit: cover;
    aspect-ratio: 1;
  }

  section {
    padding: 0 1rem;
    background-image: url(../assets/artists.png);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.5rem;
    box-shadow: inset 0 0 0 2000px rgba(0, 0, 0, 0.7);
  }

  h2 {
    margin-bottom: 1rem;
    color: white;
    width: 100%;
    font-size: 2.5rem;
    text-align: left;
    margin-left: 7rem;
    font-family: "Black_Wolf", sans-serif;
  }

  h3 {
    font-family: "Wayfarer's Toy Box", sans-serif;
    font-size: 1.75rem;
    color: gainsboro;
  }

  @media (max-width: 1000px) {
    h2 {
      margin: 0 auto;
      text-align: center;
    }
  }
</style>
