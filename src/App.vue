<template>
    <div>
      <h1>rick morty</h1>
      <ListCharacters/>
    </div>
</template>

<script>
import ListCharacters from './components/ListCharacters.vue';


export default {
  name: 'App',
  components: {
    ListCharacters
}
}
</script>


