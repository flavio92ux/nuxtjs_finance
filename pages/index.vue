<template>
  <div>
    <div>
      {{ $store.state.user }}
    </div>

    <pre>
      {{ user }}
    </pre>
  </div>

</template>

<script>
  import { mapState } from 'vuex';

  export default {
    name: 'IndexPage',

    computed: {
      ...mapState({
        user: state => state.user
      })
    }

  }
</script>
