<template>
  <div>
    <nav class="navbar navbar-dark bg-dark">
      <span class="navbar-brand mb-0 h1">Proto 3</span>
    </nav>
    <slot />
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style scope></style>
