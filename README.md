# my public web font

### font list
- Freesentaion 2.0
  - Freesentation-2.000/Freesentation-1Thin.woff2
  - Freesentation-2.000/Freesentation-2ExtraLight.woff2
  - Freesentation-2.000/Freesentation-3Light.woff2
  - Freesentation-2.000/Freesentation-4Regular.woff2
  - Freesentation-2.000/Freesentation-5Medium.woff2
  - Freesentation-2.000/Freesentation-6SemiBold.woff2
  - Freesentation-2.000/Freesentation-7Bold.woff2
  - Freesentation-2.000/Freesentation-8ExtraBold.woff2
  - Freesentation-2.000/Freesentation-9Black.woff2
- paperlogy
  - [Paperlogy-1](paperlogy/Paperlogy-1Thin.woff2)
  - paperlogy/Paperlogy-2ExtraLight.woff2
  - paperlogy/Paperlogy-3Light.woff2
  - paperlogy/Paperlogy-4Regular.woff2
  - paperlogy/Paperlogy-5Medium.woff2
  - paperlogy/Paperlogy-6SemiBold.woff2
  - paperlogy/Paperlogy-7Bold.woff2
  - paperlogy/Paperlogy-8ExtraBold.woff2
  - paperlogy/Paperlogy-9Black.woff2

### example1
```css
@font-face {
    font-family: 'Freesentation1';
    src: url('https://milkteakang.github.io/fonts/Freesentation-2.000/Freesentation-1Thin.woff2') format('woff2');
    /* font-weight: 100; */
    /* font-style: normal; */
}

* {
    font-family: Freesentation1;
}
```

### example2
```css
@font-face {
    font-family: 'Freesentation';
    src: url('https://milkteakang.github.io/fonts/Freesentation-2.000/Freesentation-1Thin.woff2') format('woff2');
    font-weight: 100;
    /* font-style: normal; */
}
@font-face {
    font-family: 'Freesentation';
    src: url('https://milkteakang.github.io/fonts/Freesentation-2.000/Freesentation-2ExtraLight.woff2') format('woff2');
    font-weight: 200;
    /* font-style: normal; */
}

.font-free-1 { font-family: Freesentation; font-weight: 100 !important; }
.font-free-2 { font-family: Freesentation; font-weight: 200 !important; }

* {
    font-family: Freesentation;
}
```