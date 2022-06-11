# Reduced Motion

Reduced all animations for performance 

## Menu

-   [Fast start](#fast-start)
-   [How to use](#how-to-use)
-   [Developer](#developer)
-   [Source Of Idea](#source-of-idea)
-   [Licanse](#licanse)

## Fast Start

Using CMD for download

```bash
  git clone https://github.com/drementer/reduced-motion.css.git
```

## How To Use

```html
<main>
    <section>Animations running</section>
</main>
```

```html
<main reduced-motion>
    <section>Animations stopped</section>
</main>
```

```html
<main reduced-motion>
    <section reduced-motion="off">Animations still running</section>
</main>
```

```html
<body reduced-motion>
    <main reduced-motion="off">
        <section reduced-motion>Animations stopped</section>
    </main>
</body>
```

Or it will be automatically fired himself
![Web Dev Video](auto-detect.gif)

## Source Of Idea
-	[web.dev](https://web.dev/prefers-reduced-motion/)
-	[sanitize.css](https://github.com/csstools/sanitize.css/blob/main/reduce-motion.css)

## Developer

-   [@drementer](https://github.com/drementer)

## Licanse

[MIT](https://choosealicense.com/licenses/mit/)
