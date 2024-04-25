<script setup lang="ts">

</script>

<template>
  <BaseApp0>
    <template v-slot:header>Напишите отзыв</template>
    <template v-slot:main>
      <h1>Напишите отзыв</h1>
      <form>
        <label>Имя</label>
        <input type="text"/>
        <label>Фамилия</label>
        <input type="text"/>
        <label>Email</label>
        <input type="email"/>
        <label>Отзыв</label>
        <textarea/>
        <button type="submit">Отправить</button>
      </form>
    </template>
  </BaseApp0>
</template>

<style scoped lang="scss">
@import "/styles/base";


form {
  @extend %boxing;

  background-color: $surface2;
  font-family: "Roboto", sans-serif;
  font-size: $size-3;
  color: $text;


  width: 70%;
  display: grid;
  gap: 1rem;


  input[type=text], input[type=email], textarea {
    @extend %boxing;
    background: $crust;
    border: none;

    font-family: "Roboto", sans-serif;
    font-size: $size-3;
    color: $text;
  }

  textarea {
    resize: none;
    width: 70%;
    height: 30rem;
  }

  input[type=text], input[type=email] {
    width: 60%;
    transition: width 0.6s ease-in-out;
  }

  input[type=text]:focus, input[type=email]:focus {
    width: 80%;
  }

  button {
    @extend %boxing;
    background: $surface0;
    border: none;

    width: 50%;

    font-family: "Roboto", sans-serif;
    font-size: $size-5;
    color: $text;

    cursor: pointer;
  }
}
</style>