<script setup lang="ts">
useSeoMeta({
      title: "C#"
    }
)
</script>

<template>
  <BaseApp0>
    <template v-slot:header>
      C Sharp
    </template>
    <template v-slot:main>
      <img src="/images/dotnet.webp" alt="c#"/>
      <h1>C#</h1>
      <p><code>C#</code> (произносится си шарп) — объектно-ориентированный язык программирования общего назначения.
        Разработан в
        1998—2001 годах группой инженеров компании Microsoft под руководством Андерса Хейлсберга и Скотта Вильтаумота
        как язык разработки приложений для платформы Microsoft .NET Framework и .NET Core. Впоследствии был
        стандартизирован как ECMA-334 и ISO/IEC 23270.
      </p>
      <p>
        <code>C#</code> относится к семье языков с C-подобным синтаксисом, из них его синтаксис наиболее близок к <code>C++</code>
        и <code>Java</code>. Язык
        имеет статическую типизацию, поддерживает полиморфизм, перегрузку операторов (в том числе операторов явного и
        неявного приведения типа), делегаты, атрибуты, события, переменные, свойства, обобщённые типы и методы,
        итераторы, анонимные функции с поддержкой замыканий, <code>LINQ</code>, исключения, комментарии в формате <code>XML</code>.
      </p>
      <p>
        Переняв многое от своих предшественников — языков <code>C++</code>, <code>Delphi</code>, Модула,
        <code>Smalltalk</code> и, в особенности, <code>Java</code> — <code>С#</code>,
        опираясь на практику их использования, исключает некоторые модели, зарекомендовавшие себя как проблематичные при
        разработке программных систем, например, <code>C#</code> в отличие от <code>C++</code> не поддерживает
        множественное наследование классов
        (между тем допускается множественная реализация интерфейсов).
      </p>
      <h2>Название</h2>
      <p>
        Название «Си шарп» (от англ. sharp — диез) происходит от буквенной музыкальной нотации, где латинской букве C
        соответствует нота До, а знак диез (англ. sharp) означает повышение соответствующего ноте звука на полутон,
        что аналогично названию языка C++, где «++» обозначает инкремент переменной. Название также является игрой с
        цепочкой C → C++ → C++++(C#), так как символ «#» можно представить состоящим из 4 знаков «+».

        Из-за технических ограничений на отображение (стандартные шрифты, браузеры и т. д.), а также из-за того, что
        знак диеза ♯ не представлен на стандартной клавиатуре компьютера, при записи имени языка программирования
        используют знак решётки (#). Это соглашение отражено в Спецификации языка C# ECMA-334. Тем не менее, на
        практике (например, при размещении рекламы и коробочном дизайне), «Майкрософт» использует знак диеза.

        Названия языков программирования не принято переводить, поэтому язык называют, используя транскрипцию, — «Си
        шарп».
      </p>
      <h2>Пример кода</h2>
      <code>
        <pre>
Console.WriteLine("Hello World!");
        </pre>
      </code>
      <br/>
      <code>
        <pre>
namespace WindowsForms;

public class Program
{
    [STAThread]
    public static void Main() => new DemoForm().ShowDialog();
}

public class DemoForm : Form
{
    Label label = new Label();

    public DemoForm()
    {
        label.Text = "Hello World!";
        this.Controls.Add(label);
        this.StartPosition = FormStartPosition.CenterScreen;
        this.BackColor = Color.White;
        this.FormBorderStyle = FormBorderStyle.Fixed3D;
    }
}
        </pre>
      </code>
    </template>
  </BaseApp0>
</template>

<style scoped lang="scss">
@import "/styles/base";

img {
  width: 40%;
  float: right;
}
</style>