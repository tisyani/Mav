## (￣y▽￣)╭ Ohohoho..... MÁV utastájékoztató

A projekt a MÁV táblázatainak egy leegyszerűsített verziója. "HTML" és "CSS" nyelveket használ fel.

### ^_^ Funkciók
-  Induló és érkező vonatok listázása 
-  Állomás, indulási és érkezési idők megjelenítése
-  Felhasználóbarát

### ☆*: .｡. o(≧▽≦)o .｡.:*☆ Használat
Csak nyitsd meg a [linket](https://tisyani.github.io/Mav/) és navigálj a gombokkal.
#### ಥ_ಥ Élő demó

A projekt élőben megtekinthető az alábbi linken:  
[MÁV Utastájékoztató](https://tisyani.github.io/Mav/)

### ╰(*°▽°*)╯ Alap HTML szerkezet
```html
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MÁV utastájékoztató</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    table {
      border-collapse: collapse;
      width: 100%;
      font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
    
    th, td {
      text-align: left;
      padding: 8px;
    }
    
</style>
```

## (^///^) CSS Stílusok
```css
tr:nth-child(even) {
    background-color: #008001;
  }
  tr:nth-child(odd) {
    background-color: #5dbe89;
```