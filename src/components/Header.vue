<template>
  <div>
    <div
      class='row'
      ref='header'
    >
      <div class='col'>
        <router-link
          to="/search/"
          tag="img"
          class='logo mt-4 mb-3 pointer'
          :src="require('@/assets/jisho_logo_full.png')"
        >
        </router-link>
      </div>
    </div>
  </div>
</template>