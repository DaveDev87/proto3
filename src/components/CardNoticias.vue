<template>
  <div class="card" style="width: 64rem;">
    <div class="card-body">
      <h5 class="card-title">{{newsData.title}}</h5>
      <h6 class="card-subtitle mb-2 text-muted">{{newsData.author}}</h6>
      <p class="card-text">{{newsData.body}}</p>
        <g-link :to="`/Noticia/${newsData.id}`">
            Seguir leyendo
        </g-link>
    </div>
  </div>
</template>

<script>
export default {
    props: ["newsData"]
};
</script>

<style></style>
