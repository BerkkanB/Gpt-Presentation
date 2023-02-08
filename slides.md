---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

# GPT ?

Nedir bu GPT ?

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Hızlıca Bakalım <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# GPT Nedir ?


- Generative Pre-trained Transformer 3 kısaca GPT-3, insanların yazdığı metinlere benzer içerik üretmek için derin öğrenmeyi kullanan bir dil modelidir.
- GPT-3 175 Milyar Parametre.
- GPT-4 ise yaklaşık 100 Trilyon parametreden oluşması bekleniyor. Bu neredeyse bir insan beynindeki nöron bağlantı sayısına eşittir.

<br>
<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
---

# GPT Nedir ?


<img border="rounded" src="https://miro.medium.com/max/720/0*TAynt0RllvotbwYt">

<br>
<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
---

# GPT Nedir ?


<img border="rounded" src="https://miro.medium.com/max/4800/0*S2MPoDKIgGj_xv2d">

<br>
<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
---

# ChatGPT Nedir ?

Nasıl oluşturulmuştur ?

- 📝 **Text-based** - ChatGPT input olarak text alan ve yine çıktı olarak bir text veren Chat Robotudur.
- 🎨 **Art** - Sanatsal cevaplar verebilir, şiir yazabilir, makale oluşturabilir ve hiç yazılmamış bir hikaye bile uydurabilir.
- 🧑‍💻 **Coding** - Verilen temada kod yazabilir, kodları okuyup yorumlayabilir, hataları düzeltebilir, kodu iyileştirebilir.

<br>
<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
---

# Nasıl Çalışır ?

Ne kullanır ?

- 📝 **Model** - OpenAI şirketinin sağladığı GPT modelini kullanır.
- 🎨 **Teknik** - Temel olarak "Text completion" tekniğini kullanır.

<br>
<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
---

# Yapay Zeka Modeli ?

Deep Learning basitçe nasıl çalışır ?

<img border="rounded" src="https://builtin.com/cdn-cgi/image/f=auto,quality=80,width=752,height=435/https://builtin.com/sites/www.builtin.com/files/styles/byline_image/public/2022-04/what-is-deep-learning.png">


<br>
<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
---
# Code

Use code snippets and get the highlighting directly![^1]

```js {all|1|2|3|3-4|all}
const completion = await openai.createCompletion({
  model: "text-davinci-003",
  prompt: generatePrompt(req.body.animal),
  temperature: 0.6,
});
```

<arrow v-click="3" x1="400" y1="420" x2="330" y2="220" color="#564" width="3" arrowSize="1" />
<arrow v-click="4" x1="400" y1="420" x2="230" y2="220" color="#564" width="3" arrowSize="1" />


[^1]: [Learn More](https://sli.dev/guide/syntax.html#line-highlighting)

<style>
.footnotes-sep {
  @apply mt-20 opacity-10;
}
.footnotes {
  @apply text-sm opacity-75;
}
.footnote-backref {
  display: none;
}
</style>


---

# Detaylar

[OpenAI](https://openai.com/api/) · [Ücretlendirme](https://openai.com/api/pricing/) · [Showcases](https://sli.dev/showcases.html)

---

# Planımız ne ?

Hangi aşamalardan geçmek istiyoruz ?

- 📝 **İlk olarak** - Hem GPT konusunda tecrübelenmek hem de ortaya kullanılabilir, bir amaca hizmet eden ve müşteriye de bir ürün olarak ulaşıp geri dönüşlerle bizi geliştirebilecek olan bir teknoloji geliştirmek istiyoruz.
<br>
- Bunun içinse öncelikle Resume-Recommender sistemini hayata geçirmeyi planlıyoruz.
- Daha sonrasında buradan edineceğimiz tecrübelerle daha kapsamlı ve daha büyük projelerle ilerlemek istiyoruz.
- Örnek olarak Performans Değerlendirme Sistemi.

<br>
<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->
---

# Resume Recommender 

CV öneri sistemi

Ortaya ne çıkarmak istiyoruz ? 
- CV havuzundan proje ve ekip ihtiyaçlarına uygun adayları 
bulup, yorumlayan ve öneri sunan bir yapay zeka sistemi.

 Nasıl yapıyoruz ? 
- Havuzda bulunan CV’ler ve ihtiyaçların belirtildiği 
parametrelerle birlikte OpenAI’ın sunmuş olduğu GPT-3 
(Text-Completion) modelini kullanarak, senaryoya en 
uygun adayları belirliyoruz.

 Nasıl fayda sağlamasını amaçlıyoruz ? 
- CV inceleme aşamasını otomatize ederek insan hatalarının, 
harcanan zaman ve eforun minimuma indirilmesi 
amaçlanmaktadır.

<br>
<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->
