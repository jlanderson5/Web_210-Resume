const prevBtn = document.querySelector(".prev-btn");
const nextBtn = document.querySelector(".next-btn");
const carouselSlide = document.querySelector(".carousel-slide");

let slideIndex = 0;

nextBtn.addEventListener("click", () => {
  slideIndex++;
  carouselSlide.style.transform = `translateX(${-slideIndex * 100}%)`;
});

prevBtn.addEventListener("click", () => {
  slideIndex--;
  carouselSlide.style.transform = `translateX(${-slideIndex * 100}%)`;
});
