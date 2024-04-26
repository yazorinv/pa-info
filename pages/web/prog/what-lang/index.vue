<script setup lang="ts">
</script>


<template>
  <BaseApp0>
    <template v-slot:header>
      Анкета
    </template>
    <template v-slot:main>
      <h1>Какие ЯП Вы знаете?</h1>
      <form>
        <label>Сколько Вам лет?</label>
        <input type="number"/>
        <label>Ваш пол</label>
        <select>
          <option>Мужской</option>
          <option>Женский</option>
        </select>
        <label>Ваш любимый ЯП</label>
        <select>
          <option>нет</option>
          <option>C++</option>
          <option>C</option>
          <option>Java</option>
          <option>Python</option>
          <option>Rust</option>
          <option>C#</option>
          <option>JavaScript</option>
          <option>Kotlin</option>
          <option>Pascal</option>
          <option>PHP</option>
          <option>Swift</option>
          <option>Go</option>
          <option>Ruby</option>
          <option>Scala</option>
        </select>
        <label>Какие ЯП Вы знаете?</label>
        <span><input type="checkbox"/> C++</span>
        <span><input type="checkbox"/> C</span>
        <span><input type="checkbox"/> Java</span>
        <span><input type="checkbox"/> Python</span>
        <span><input type="checkbox"/> Rust</span>
        <span><input type="checkbox"/> C#</span>
        <span><input type="checkbox"/> JavaScript</span>
        <span><input type="checkbox"/> Kotlin</span>
        <span><input type="checkbox"/> Pascal</span>
        <span><input type="checkbox"/> PHP</span>
        <span><input type="checkbox"/> Swift</span>
        <span><input type="checkbox"/> Go</span>
        <span><input type="checkbox"/> Ruby</span>
        <span><input type="checkbox"/> Scala</span>

        <p><input type="checkbox"> Вы любите программировать?</p>
        <label>Вы любите котов?</label>
        <select>
          <option>скорее да</option>
          <option>да</option>
          <option>yes</option>
          <option>однозначно</option>

        </select>
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


  input, select, textarea {
    @extend %boxing;
    background: $crust;
    border: none;

    font-family: "Roboto", sans-serif;
    font-size: $size-3;
    color: $text;
  }

  input[type=checkbox] {
    width: 1rem;
    height: 1rem;

    margin-right: 1rem;
    cursor: pointer;
  }

  textarea {
    resize: none;
    width: 70%;
    height: 30rem;
  }

  input[type=text], input[type=number], select {
    width: 40%;
    transition: width 0.6s ease-in-out;
  }

  input[type=text]:focus, input[type=number]:focus {
    width: 50%;
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

  select {
    display: flex;
    // grid-template-columns: 1fr 1fr 1fr;
  }
}
</style>
