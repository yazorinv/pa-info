<script setup lang="ts">
useSeoMeta({
      title: "Rust"
    }
)
</script>

<template>
  <BaseApp0>
    <template v-slot:header>
      Rust
    </template>
    <template v-slot:main>
      <img
          src="/images/rust.webp"
          alt="rust"/>
      <h1>Rust</h1>
      <p>
        Rust (Раст, [rʌst]; rust с англ. — «ржавчина») — мультипарадигменный компилируемый язык программирования общего
        назначения, сочетающий парадигмы функционального и процедурного программирования с объектной системой,
        основанной
        на типажах. Управление памятью осуществляется через механизм «владения» с использованием аффинных типов,
        что позволяет обходиться без системы сборки мусора во время исполнения программы. Rust гарантирует безопасную
        работу с памятью благодаря встроенной в компилятор системе статической проверки ссылок (borrow checker). Имеются
        средства, позволяющие использовать приёмы объектно-ориентированного программирования.
      </p>
      <p>
        Ключевые приоритеты языка: безопасность, скорость и параллелизм. Rust пригоден для системного программирования,
        в
        частности, он рассматривается как перспективный язык для разработки ядер операционных систем. Rust сопоставим
        по скорости и возможностям с C++/Си, однако даёт большую безопасность при работе с памятью, что обеспечивается
        встроенными в язык механизмами контроля ссылок. Производительности программ на Rust способствует использование
        «абстракций с нулевой стоимостью».
      </p>
      <h2>История</h2>
      <img src="/images/rust1.webp"
           alt="rust"/>
      <p>
        Работа над языком была начата сотрудником Mozilla Грэйдоном Хором в 2006 году. Автор дал проекту название Rust,
        по его словам, связанное с грибами семейства ржавчинные (англ. rust fungi).
      </p>
      <p>
        В 2009 году компания Mozilla начала отдельно спонсировать разработку Rust. Спустя год язык был официально
        представлен на Mozilla Summit 2010. Изначальный компилятор, реализованный на OCaml, был заменён на новый,
        написанный на Rust и использовавший LLVM для генерации машинного кода; в следующем году новый компилятор
        впервые успешно скомпилировал сам себя.
      </p>
      <p>
        Первая официальная альфа-версия Rust (0.1) была выпущена в январе 2012 года.
      </p>
      <p>
        В апреле 2013 года был запущен Servo — экспериментальный проект компании Mozilla по разработке браузерного
        движка на Rust.
      </p>
      <p>
        Первая стабильная версия Rust (1.0) вышла в мае 2015 года. Программные интерфейсы и возможности языка
        подверглись значительной ревизии, после которой по умолчанию оставлены только полностью готовые к применению
        возможности, реализация которых не будет изменяться в дальнейшем. Все остальные функции переведены в разряд
        экспериментальных и вынесены из поставки по умолчанию.
      </p>
      <p>
        В декабре 2022 года Rust стал первым языком, кроме C и ассемблера, который поддерживается при разработке ядра
        Linux.
      </p>
      <p>
        Microsoft переписывает отдельные элементы собственной экосистемы программных продуктов на языке программирования
        Rust; так, в 2024 г. фундаментальный серверный компонент, обеспечивающий работу набора облачных сервисов
        Microsoft 365 будет переписан на этом языке.
      </p>
      <h2>Пример кода</h2>
      <code>
        <pre>
fn main() {
    println!("Hello, world!");
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