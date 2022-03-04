<template>
  <div>
    <form action="">
      <input type="text" placeholder="Nome">
      <hr>
      <input type="email" placeholder="E-mail">
      <hr>
      <input type="number" placeholder="Idade">
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

    }
  },
}
</script>
<style scoped>

</style>
