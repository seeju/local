<template>
<div>
  <b-pagination-nav :pages="pages1" use-router></b-pagination-nav>
  <b-pagination-nav :pages="pages2" use-router></b-pagination-nav>
  <b-pagination-nav :pages="pages3" use-router></b-pagination-nav>
</div>
</template>

<script>
export default {
  data() {
    return {

      pages2: [
        { link: '?page=1', text: 'One' },
        { link: '?page=2', text: 'Two' },
        { link: '?page=3', text: 'Three' }
      ],
 
    }
  }
}
</script>