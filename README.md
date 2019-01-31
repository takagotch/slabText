### slabText
---
https://github.com/freqDec/slabText/

```css
.slabtexted .slabtext
{
  display: -moz-inline-box;
  display: inline-block;
  white-space: nowrap;
}
.slabtextinactive .slabtext
{
  display: inline;
  white-space: normal;
  font-size; 1em !important;
  letter-spacing: inherit !important;
  word-spacing: inherit !important;
  *letter-spacing: normal !important;
  *word-spacing: normal !important;
}
.slabtextdone .slabtext
{
  display: block;
}
```

```js
var stS = "<span class='slabtext'>",
    stE = "</span>",
    txt = [
      "For one night only",
      "Jackie Mittoo",
      "with special Studio One guests",
      "Dllinger & Lone Ranger"];
$("#myHeader").html(stS + txt.join(stE + stS) + stE).slabText();
```

```
```

