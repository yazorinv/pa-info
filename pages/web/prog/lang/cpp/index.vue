<script setup lang="ts">
useSeoMeta({
      title: "C++"
    }
)
</script>


<template>
  <BaseApp0>
    <template v-slot:header>
      C++
    </template>
    <template v-slot:main>
      <img src="/images/cpp-logo.webp" alt="cpp logo"/>
      <h1>C++</h1>
      <p>
        Языку <code>C++</code> почти 40 лет, но он по-прежнему актуален и востребован: сегодня он применяется
        повсеместно — от
        разработки игр и десктопных программ до «мозгов» умного дома.
      </p>
      <figure style="font-style: italic">
        <h6>Бьерн Страуструп:</h6>
        <p>«Эволюция необходима для того, чтобы справляться с вызовами меняющегося мира и реализовывать новые идеи».
          ("Evolution is necessary to meet the challenges of a changing world and to incorporate new ideas.")</p>
      </figure>
      <p>
        <code>C++</code> (читается си-плюс-плюс) — компилируемый, статически типизированный язык программирования общего
        назначения.
      </p>
      <p>
        Поддерживает такие парадигмы программирования, как процедурное программирование, объектно-ориентированное
        программирование, обобщённое программирование. Язык имеет богатую стандартную библиотеку, которая включает в
        себя распространённые контейнеры и алгоритмы, ввод-вывод, регулярные выражения, поддержку многопоточности и
        другие возможности. <code>C++</code> сочетает свойства как высокоуровневых, так и низкоуровневых языков. В
        сравнении с
        его предшественником — языком <code>C</code> — наибольшее внимание уделено поддержке объектно-ориентированного и
        обобщённого
        программирования.</p>
      <p>
        <code>C++</code> широко используется для разработки программного обеспечения, являясь одним из самых популярных
        языков
        программирования. Область его применения включает создание операционных систем,
        разнообразных прикладных программ, драйверов устройств, приложений для встраиваемых систем,
        высокопроизводительных серверов, а также компьютерных игр. Существует множество реализаций языка
        <code>C++</code>, как
        бесплатных, так и коммерческих и для различных платформ. Например, на платформе x86 это GCC, Clang, Visual
        <code>C++</code>,
        Intel <code>C++</code> Compiler, Embarcadero (Borland) <code>C++</code> Builder и другие. <code>C++</code>
        оказал огромное влияние на другие языки
        программирования, в первую очередь на <code>Java</code> и <code>C#</code>.</p>
      <p>
        Синтаксис <code>C++</code> унаследован от языка <code>C</code>. Изначально одним из принципов разработки было
        сохранение
        совместимости с
        <code>C</code>. Тем не менее <code>C++</code> не является в строгом смысле надмножеством <code>C</code>;
        множество программ, которые могут
        одинаково
        успешно транслироваться как компиляторами <code>C</code>, так и компиляторами <code>C++</code>, довольно велико,
        но не
        включает все
        возможные программы на <code>C</code>.
      </p>
      <h2>История</h2>
      <p>
        Язык возник в начале 1980-х годов, когда сотрудник фирмы Bell Labs Бьёрн Страуструп придумал ряд
        усовершенствований к языку <code>C</code> под собственные нужды. Когда в конце 1970-х годов Страуструп начал работать в
        Bell Labs над задачами теории очередей (в приложении к моделированию телефонных вызовов), он обнаружил, что
        попытки применения существовавших в то время языков моделирования оказались неэффективными, а применение
        высокоэффективных машинных языков слишком сложно из-за их ограниченной выразительности. Так, язык Симула имеет
        такие возможности, которые были бы очень полезны для разработки большого программного обеспечения, но работает
        слишком медленно, а язык <code>BCPL</code> достаточно быстр, но слишком близок к языкам низкого уровня и не подходит для
        разработки большого программного обеспечения.
      </p>
      <h2>Философия C++</h2>
      <p>
        В книге «Дизайн и эволюция <code>C++</code>» Бьёрн Страуструп описывает принципы, которых он придерживался при
        проектировании
        <code>C++</code>. Эти принципы объясняют, почему <code>C++</code> именно такой, какой он есть. Некоторые из них:
      </p>
      <ul>
        <li>Получить универсальный язык со статическими типами данных, эффективностью и переносимостью языка
          <code>C</code></li>
        <li>Непосредственно и всесторонне поддерживать множество стилей программирования, в том числе процедурное
          программирование, абстракцию данных, объектно-ориентированное программирование и обобщённое программирование
        </li>
        <li>Дать программисту свободу выбора, даже если это даст ему возможность выбирать неправильно</li>
        <li>Максимально сохранить совместимость с <code>C</code>, тем самым делая возможным лёгкий переход от
          программирования на <code>C</code>
        </li>
        <li>Избежать разночтений между <code>C</code> и <code>C++</code>: любая конструкция, допустимая в обоих языках,
          должна в
          каждом из них
          обозначать одно и то же и приводить к одному и тому же поведению программы
        </li>
        <li>Избегать особенностей, которые зависят от платформы или не являются универсальными</li>
        <li>«Не платить за то, что не используется» — никакое языковое средство не должно приводить к снижению
          производительности программ, не использующих его
        </li>
        <li>Не требовать слишком усложнённой среды программирования</li>
      </ul>
      <h3>Пример моего кода C++</h3>
      <code>
        <pre>
#include &lt;bits/stdc++.h&gt;

using namespace std;
using namespace chrono;


#pragma GCC optimize("Ofast")
#pragma GCC target("avx2")


using ll = long long;
using ull = unsigned long long;
using uint = unsigned int;
using ld = long double;


constexpr ll INF = static_cast&lt;ll>(2e18 + 7);
constexpr ll MOD = static_cast&lt;ll>(1e9 + 7);
constexpr ld EPS = 1e-9l;


void solve(istream& cin, ostream& cout);

int tests = 1, test_num = 0;
int main() {
    ios_base::sync_with_stdio(false);
    cin.tie(nullptr);

    // cin >> tests;
    for (test_num = 0; test_num < tests; ++test_num)
        solve(cin, cout);
}


struct SegTree {
    vector&lt;ll> v;
    ll _size = 0;


    void _push(ll i) {
        if (v[i] == 0)
            return;
        v[i * 2] = v[i * 2 + 1] = v[i];
        v[i] = 0;
    }


    ll _read(ll i, ll first, ll last, ll pos) {
        if (first >= last)
            return 0;
        if (first <= pos && pos < last) {
            if (last - first == 1)
                return v[i];
            ll middle = (first + last) / 2;
            _push(i);

            return _read(i * 2, first, middle, pos) + _read(i * 2 + 1, middle, last, pos);
        }
        return 0;
    }


    void _write(ll i, ll first, ll last, ll L, ll R, ll x) {
        if (first >= last)
            return;
        if (L <= first && last <= R) {
            v[i] = x;
            return;
        }
        if (first < R && L < last) {
            ll middle = (first + last) / 2;
            _push(i);

            _write(i * 2, first, middle, L, R, x);
            _write(i * 2 + 1, middle, last, L, R, x);
        }
    }


    SegTree(const vector&lt;ll>& a) {
        for (_size = 1; _size < a.size();)
            _size *= 2;
        v.resize(_size * 2, 0);

        for (ll i = 0; i < a.size(); ++i)
            v[i + _size] = a[i];
    }


    void write(ll first, ll last, ll x) {
        _write(1, 0, _size, first, last, x);
    }


    void update_all() {
        for (ll i = 1; i < _size; ++i)
            _push(i);
    }


    ll operator()(ll i) {
        return _read(1, 0, _size, i);
    }


    ll operator[](ll i) const {
        return v[i + _size];
    }
};


void solve(istream& cin, ostream& cout) {
    ll n;
    cin >> n;
    vector&lt;ll> a(n);
    vector&lt;deque&lt;ll>> v(3e5 + 1);
    for (ll i = 0; i < n; ++i) {
        cin >> a[i];
        v[a[i]].push_back(i);
    }
    SegTree st(a);

    ll m;
    cin >> m;
    while (m--) {
        ll c;
        cin >> c;
        while (!v[c].empty() && st(v[c].back()) != c)
            v[c].pop_back();
        while (!v[c].empty() && st(v[c].front()) != c)
            v[c].pop_front();

        if (v[c].size() >= 2)
            st.write(v[c].front(), v[c].back(), c);
    }


    st.update_all();
    for (ll i = 0; i < n; ++i)
        cout << st[i] << ' ';
}

        </pre>
      </code>
    </template>
  </BaseApp0>
</template>


<style scoped lang="scss">
@import "/styles/base";

img {
  width: 50%;
  float: right;
}
</style>
