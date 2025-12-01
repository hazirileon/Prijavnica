# PRIJAVNICA (html, css)
## *Zgled:*
![image alt](https://github.com/hazirileon/Private/blob/0ac321e011fca3bd10ac7d55a55a5d44af5b2daf/Posnetek%20zaslona%202025-09-29%20103056%20(1).jpg)
## *POSTOPEK*
#### 1.Tabela
- za ustvarit tabelo smo uporabili po `<table>`
- za ustvarit vrstice `<tr>`, za vstavit vrstice pa `<td>`

#### 2.Form
- preden vnesemo `<table>` moramo vnesti `<form>`, ker s pomočjo tega nam bo vse funkcioniralo

> `<label>` meaning?
- oznaka `<label>` določa oznako za številne obrazčne elemente.
- element `<label>` je uporaben za uporabnike bralnikov zaslona, saj bo bralnik zaslona prebral oznako na glas, ko se uporabnik osredotoči na vnosni element.

>uporaba `<imput>`

| Vrsta | Opis |
| --- | --- |
| `<input type="text">` | Prikaže enovrstično vnosno polje za besedilo | 
| `<input type="radio">` | Prikaže izbirni gumb (za izbiro ene izmed mnogih možnosti) | 
| `<input type="checkbox">` | Prikaže potrditveno polje (za izbiro nič ali več možnosti) | 
| `<input type="submit">` | Prikaže gumb za oddajo (za pošiljanje obrazca) | 
| `<input type="buttom">` | Prikaže klikabilni gumb | 

#### Zgled
```html
<label for="ime">Ime:</label>
<input type="text" id="ime" name="ime" value=""><br>
```
↓
<label for="ime">Ime:</label><input type="text" id="ime" name="ime" value=""><br>
_____________________________________________________________
```html
<label for="spol">Spol:</label></td>
<input type="radio" id="moski" name="spol" value="M">
<label for="html">M</label>
<input type="radio" id="zenska" name="spol" value="Ž">
<label for="css">Ž</label><br>
```
↓
<label for="spol">Spol:</label></td><input type="radio" id="moski" name="spol" value="M"><label for="html">M</label>  <input type="radio" id="zenska" name="spol" value="Ž"><label for="css">Ž</label><br>
___________________________________________________________
Za države sem šel na →[države](https://gist.github.com/nateluzod/1037153)
