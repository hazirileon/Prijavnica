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
![image alt](https://github.com/hazirileon/Private/blob/68a072d1b2f6c5b0633bacb854368f6ba64a7366/Posnetek%20zaslona%202025-12-01%20185511.png)
_____________________________________________________________
```html
<label for="spol">Spol:</label></td>
<input type="radio" id="moski" name="spol" value="M">
<label for="html">M</label>
<input type="radio" id="zenska" name="spol" value="Ž">
<label for="css">Ž</label><br>
```
![image alt](https://github.com/hazirileon/Private/blob/68a072d1b2f6c5b0633bacb854368f6ba64a7366/Posnetek%20zaslona%202025-12-01%20185520.png)
___________________________________________________________
```html
<label for="placilo">Plačilo:</label></td>
<input type="checkbox" id="gotovina1" name="gotovina" value="EUR">
<label for="gotovina1">EUR</label><br>
<input type="checkbox" id="gotovina2" name="gotovina" value="USD">
<label for="gotovina2">USD</label><br>
<input type="checkbox" id="gotovina3" name="gotovina" value="GBP">
<label for="gotovina3">GBP</label><br>
<input type="checkbox" id="gotovina4" name="gotovina" value="CHF">
<label for="gotovina4">CHF</label><br>
<input type="checkbox" id="gotovina5" name="gotovina" value="HRK">
<label for="gotovina5">HRK</label><br>
```
![image alt](https://github.com/hazirileon/Private/blob/6ee72dcfaf70d04c664a5c2610c52a27d9f2473b/Posnetek%20zaslona%202025-12-03%20095322.png)
___________________________________________________________
```html
<label for="drzave">Država:</label></td>
<input list="drzave" name="drzave">
<datalist id="drzave">
<option value="Afghanistan">Afghanistan</option>
<option value="Albania">Albania</option>
<option value="Algeria">Algeria</option>
<option value="Andorra">Andorra</option>
<option value="Angola">Angola</option>
<option value="Antigua and Barbuda">Antigua and Barbuda</option>
<option value="Argentina">Argentina</option>
<option value="Armenia">Armenia</option>
itd.
```
Za države sem šel na →[države](https://gist.github.com/nateluzod/1037153)

![image alt](https://github.com/hazirileon/Private/blob/3afd739801bc05218d373b480983342570a5a8d0/Posnetek%20zaslona%202025-12-03%20095447.png)
___________________________________________________________
```
<input type="submit" value="Sperjmi"><br><input type="reset" value="Počisti">
```
![image alt](https://github.com/hazirileon/Private/blob/3afd739801bc05218d373b480983342570a5a8d0/Posnetek%20zaslona%202025-12-03%20095455.png)