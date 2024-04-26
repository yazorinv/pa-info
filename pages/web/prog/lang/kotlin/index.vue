<script setup lang="ts">

</script>

<template>
  <BaseApp0>
    <template v-slot:header>
      Kotlin
    </template>
    <template v-slot:main>

      <h1>Kotlin</h1>
      <img
          src="https://kotlinlang.org/docs/images/kotlin-logo.png"
          alt="kotlin"/>
      <p>
        Kotlin (Ко́тлин) — статически типизированный, объектно-ориентированный язык программирования, работающий поверх
        Java Virtual Machine и разрабатываемый компанией JetBrains. Также компилируется в JavaScript и в исполняемый код
        ряда платформ через инфраструктуру LLVM. Язык назван в честь российского острова Котлин в Финском заливе, на
        котором расположен город Кронштадт.
      </p>
      <p>
        Авторы ставили целью создать язык более лаконичный и типобезопасный, чем Java, и более простой, чем Scala.
        Следствием упрощения по сравнению со Scala стали также более быстрая компиляция и лучшая поддержка языка в
        IDE. Язык полностью совместим с Java, что позволяет Java-разработчикам постепенно перейти к его
        использованию; в частности, язык также встраивается Android, что позволяет для существующего Android-приложения
        внедрять новые функции на Kotlin без переписывания приложения целиком.
      </p>
      <img src="https://www.clipartmax.com/png/middle/238-2381243_safeness-kotlin-android-logo.png" alt="kotlin">
      <h2>История</h2>
      <p>
        Язык разрабатывается с 2010 года под руководством Андрея Бреслава, представлен общественности в июле
        2011. Исходный код реализации языка открыт в феврале 2012. В феврале выпущен milestone 1, включающий
        плагин для IDEA. В июне — milestone 2 с поддержкой Android. В декабре 2012 года вышел milestone 4,
        включающий, в частности, поддержку Java 7.
      </p>
      <p>
        В феврале 2016 года вышел официальный релиз-кандидат версии 1.0, а 15 февраля 2016 года — релиз 1.0. 1
        марта 2017 вышел релиз 1.1.
      </p>
      <p>
        В мае 2017 года компания Google сообщила, что инструменты языка Kotlin, основанные на JetBrains IDE, будут по
        стандарту включены в Android Studio 3.0 — официальный инструмент разработки для ОС Android.
      </p>
      <p>
        На Google I/O 2019 было объявлено, что язык программирования Kotlin стал приоритетным в разработке под
        Android.
      </p>
      <p>
        В ноябре 2020 года Бреслав объявил об уходе из JetBrains, руководство разработкой языка было передано Роману
        Елизарову.
      </p>
      <h2>Пример кода</h2>
      <code>
        <pre>
fun main() {
  val scope = "world"
  println("Hello, $scope!")
}
        </pre>
      </code>
      <br/>
      <code>
        <pre>
fun sayHello(maybe: String?, neverNull: Int) {
   // use of elvis operator
   val name: String = maybe ?: "stranger"
   println("Hello $name")
}
        </pre>
      </code>
    </template>
  </BaseApp0>
</template>

<style scoped lang="scss">
@import "/styles/base";

img {
  width: 30%;
  float: right;
}
</style>