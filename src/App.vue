<template lang="pug">
  #app
    .container
      .row
        .col-12.text-center
          #nav
            router-link(to='/') Home
            | &nbsp;|&nbsp;
            router-link(to='/about') About
            | &nbsp;|&nbsp;
            router-link(to='/cart') Cart
        .col-12
          router-view
</template>
