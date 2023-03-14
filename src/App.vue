<template>
  <word-cloud :words="words" />
</template>

<script>
import WordCloud from './components/WordCloud.vue'

export default {
  name: 'App',
  components: {
    WordCloud
  },
  data() {
    return {
      words: [
        { word: "alice", count: 112 },
        { word: "attempts", count: 104 },
        { word: "onlooking", count: 103 },
        { word: "queen", count: 91 },
        { word: "said", count: 89 },
        { word: "so", count: 83 },
        { word: "like", count: 75 },
        { word: "time", count: 72 },
        { word: "little", count: 67 },
        { word: "king", count: 63 },
        { word: "looking", count: 62 },
        { word: "glass", count: 62 },
        { word: "turtle", count: 58 },
        { word: "way", count: 57 },
        { word: "humpty", count: 57 },
        { word: "dumpty", count: 56 },
        { word: "round", count: 54 },
        { word: "great", count: 54 },
        { word: "mock", count: 54 },
        { word: "hatter", count: 53 },
        { word: "white", count: 53 },
        { word: "see", count: 52 },
        { word: "say", count: 51 },
        { word: "went", count: 50 },
        { word: "two", count: 49 },
        { word: "first", count: 49 },
        { word: "said,", count: 48 },
        { word: "certainly", count: 46 },
        { word: "way.", count: 45 },
        { word: "heads", count: 44 },
        { word: "voice", count: 43 },
        { word: "though", count: 42 },
        { word: "went,", count: 42 },
        { word: "march", count: 41 },
        { word: "quite", count: 40 },
        { word: "soon", count: 40 },
        { word: "looking-glass,", count: 40 },
        { word: "queen.", count: 39 },
        { word: "better", count: 39 },
        { word: "must", count: 38 },
        { word: "way,", count: 38 },
        { word: "majesty", count: 38 },
        { word: "rabbit", count: 38 },
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
