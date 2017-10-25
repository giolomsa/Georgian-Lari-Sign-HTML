# Georgian-Lari-Sign-HTML
Georgian Lari Sign '₾' in HTML Using CSS3 font face

Usage: 
1) include css file in your project 

```sh
<link rel="stylesheet" type="text/css" href="css/styles.css">
```

  or just copy font face in your exist css file
  
  ```sh
@font-face {
  font-family: 'LariFont';
  src: url('../fonts/LariSymbolV2.eot?#iefix') format('embedded-opentype'),  url('../fonts/LariSymbolV2.woff') format('woff'), url('../fonts/LariSymbolV2.ttf')  format('truetype'), url('../fonts/LariSymbolV2.svg#LariSymbolV2') format('svg');
  font-weight: normal;
  font-style: normal;
}

.lari{
	font-family: LariFont;
}

```

2) Copy fonts folder to your root folder

3) Use class lari wherever you want to use Lari Symbol

```sh
<span class="lari">4</span>
```

Works in all browsers.

Enjoy.
