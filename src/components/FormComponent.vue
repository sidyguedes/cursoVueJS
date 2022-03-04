<template>
  <div>
    <form action="">
      <input type="text" v-model="userData.user" placeholder="Nome">
      <hr>
      <input type="email" v-model="userData.email" placeholder="E-mail">
      <hr>
      <input type="number" v-model="userData.age" placeholder="Idade">
      <hr>
      <input type="radio" name="" id="">Masculino  |
      <input type="radio" name="" id="">Feminino
      <hr>
      <select name="" id="">
        <option value="">Selecione o estado</option>
        <option value="SP">São Paulo</option>
        <option value="RJ">Rio de Janeiro</option>
        <option value="MG">Minas Gerais</option>
      </select>
      <hr>
      <input type="checkbox" name="" id="">
      <label for="">Concordo com os termos de uso</label>
      <hr>
      <textarea name="" id="" cols="30" rows="10"></textarea>
      <hr>
      <button type="submit">Enviar</button>
    </form>
  </div>
</template>
<script>
export default {
  data(){
    return{
      userData: {
        user: null,
        email: null,
        age: null,
        sex: null,
        province: null,
      },
      terms: true,
      desc: null,
    }
  },
}
</script>
<style scoped>

</style>
