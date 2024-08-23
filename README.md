# my public web font

### font list
- Freesentaion 2.0
- paperlogy

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