# Reduced Motion

Proje açıklaması

## Menu

-   [Hızlı Başlangıç](#hızlı-başlangıç)
-   [Kullanım/Örnekler](#Kullanım/Örnekler)
-   [Geliştirici](#geliştirici)
-   [Lisans](#lisans)

## Hızlı Başlangıç

Terminal kullanarak indir

```bash
  git clone https://github.com/drementer/reduced-motion.css.git
```

## Kullanım/Örnekler

```html
<main>
    <section>// Animations running</section>
</main>
```

```html
<main reduced-motion>
    <section>// Animations stopped</section>
</main>
```

```html
<main reduced-motion>
    <section reduced-motion="off">// Animations still running</section>
</main>
```

```html
<body reduced-motion>
    <main reduced-motion="off">
        <section reduced-motion>// Animations stopped</section>
    </main>
</body>
```

Or it will be automatically fired himself
![](/auto-detect.mp4.gif)

## Geliştirici

-   [@drementer](https://github.com/drementer)

## Lisans

[MIT](https://choosealicense.com/licenses/mit/)
