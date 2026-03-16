<template>
  <header>
    <div>
      <h2>J&J</h2>
      <p>June 23rd, 2025</p>
    </div>
    <nav>
        <ul>
          <li><a href="#">HOME</a></li>
          <li><a href="#">OUR STORY</a></li>
          <li><a href="#">DETAILS</a></li>
          <li><a href="#">RSVP</a></li>
        </ul>
    </nav>
  </header>
</template>
<style scooped>
header{
  font-size: 1.4rem;
  background-color: #696766;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
header div {
  align-items: center;
  display: flex;
  gap: 10px;
}
header div h2{
  font-size: 2rem;
}
header nav ul {
  display: flex;
  gap: 4rem;
}
header nav ul li a {
  text-decoration: underline;
}
h2, p, a {
  color: white;
}
@media screen and (max-width: 768px) {
header{
  font-size: 12px;
  padding: 1rem 1rem;
}
header div {
  gap: 10px;
}
header div h2{
  font-size: 1rem;
}
header nav ul {
  gap: 1rem;
}
}
</style>
