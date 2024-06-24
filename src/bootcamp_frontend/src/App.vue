<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
   <h1>siema</h1>
   <h2>jestem tu nowy</h2>
   <br>
   <button @click="podbij">podbij</button>
   {{ licznik }}
  </main>
</template>

<script>
export default{
  data(){
    return {
      licznik: 0
    }
  },
  methods: {
    podbij(){
      this.licznik++
    }
  }
}

</script>
