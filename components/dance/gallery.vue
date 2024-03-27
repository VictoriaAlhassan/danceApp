<template>
  <div class="image-gallery">
    <img src="/static/gallery-image-1.jpeg" alt="Image 1" />
    <img src="/static/gallery-image-2.jpeg" alt="Image 2" />
    <img src="/static/gallery-image-3.jpeg" alt="Image 3" />
    <img src="/static/gallery-image-4.jpeg" alt="Image 4" />
    <img src="/static/gallery-image-5.jpeg" alt="Image 5" />
    <img src="/static/gallery-image-6.jpeg" alt="Image 6" />
    <img src="/static/gallery-image-7.jpeg" alt="Image 7" />
    <img src="/static/gallry-image-8.jpeg" alt="Image 8" />
    <img src="/static/gallery-image-9.jpeg" alt="Image 9" />
    <img src="/static/gallery-image-10.jpeg" alt="Image 10" />
    <img src="/static/gallery-image-11.jpeg" alt="Image 11" />
    <img src="/static/gallery-image-12.jpeg" alt="Image 12" />
  </div>
</template>

<style scoped>
.image-gallery {
  display: grid;
  grid-template-columns: repeat(4, 1fr minmax(200px, 1fr));
}

.image-gallery img {
  width: 100%;
  height: auto;
  object-fit: cover;
  transition: transform 0.3s ease-in-out;
}

.image-gallery img:hover {
  transform: scale(1.1);
  opacity: 0.8;
}
</style>
