<template>
 <main>
  <section class="banner">
    <h1>JANNY & JASON</h1>
    <div>
    <p class="P1">With love and gratitude, we invite you to share in the joy of our wedding day.</p>
    <p>Saturday, September 20, 2025 The Golden Elm Manor, St.Augustine, New York</p>
  </div>
  </section>
  <section class="cards">
    <ul>
      <li>
        <a href="#">
          <img src="/imageUm.png" alt="img">
          <span class="texto">OUR STORY</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="/imageDois.png" alt="img">
          <span class="texto">THE DETAILS</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="/imageTres.png" alt="img">
          <span class="texto">RSVP</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="/imageQuatro.png" alt="img">
          <span class="texto">REGISTRY</span>
        </a>
      </li>
    </ul>
  </section>
  <section class="log-on">
    <h2>REGISTRY</h2>
    <p>Your presence is the greatest gift we could ask for. For those who wish to honor us with a contribution, we have created a honeymoon registry to help us begin a beautiful new chapter together along the Amalfi Coast.</p>
    <button>GO TO REGISTRY</button>
  </section>
  <section class="mensage">
    <button>Mensagen</button>
  </section>
 </main>
</template>

<style scoope>
main section.banner div {
  background-image: url(/public/banner.png);
  padding: 10vw 0 20vw 0;
  justify-content: center;
  background-size: cover;
  background-repeat: no-repeat;
}main section.banner div p {
  text-align: center;
  font-size: 2vw;
  margin: 0 44rem;
}
main section.banner div p.P1 {
  margin: 0 38rem 5vw 38rem;
}
main section.banner h1 {
  font-size: 10vw;
  text-align: center;
  color: black;
}
main section.cards ul li {
  list-style: none;
}
main section.cards ul li a {
  position: relative;
  display: inline-block;
}
main section.cards ul li a span.texto {
  font-size: 2vw;
  color: rgb(255, 255, 255);
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-decoration: underline;
}
main section.cards ul {
  display:grid ;
  grid-template-columns: max-content max-content;
  justify-content: center;
  gap: 5vw;
  }
  main section.cards ul li a img {
    width: 26vw;
    height: 30vw;
    object-fit: cover;
    border-radius: 2vw;
  }
  main section.cards {
    margin: 5vw 0;
  }
  main section.log-on {
    background-image: url(/imageLogOn.png);
    padding: 10vw 0 15vw 0;
    justify-content: center;
    background-size: cover;
    background-repeat: no-repeat;
    object-fit: cover;
    text-align: center;
  }
  main section.log-on h2 {
    font-size: 2.5vw;
    margin: 0 0 2vw 0;
  }
  main section.log-on p {
    font-size: 2vw;
    margin: 5vw 25vw;
  }
  main section.log-on button {
    color: white;
    font-size: 2vw;
    background-color: #7C7661;
    padding: 1vw 8vw;
    border-radius: 4vw;
  }
  main section.mensage {
    background-image: url(/mensage.png);
    padding: 10vw 0 10vw 0;
    justify-content: center;
    background-size: cover;
    background-repeat: no-repeat;
    object-fit: cover;
    text-align: center;
  }
  main section.mensage button {
    margin: 10vw 0 0 0;
    color: #EFBF04;
    background-color: #823131;
    padding: 2vw 8vw;
    font-size: 3vw;
    border: 15px solid #EFBF04;

  }
</style>
