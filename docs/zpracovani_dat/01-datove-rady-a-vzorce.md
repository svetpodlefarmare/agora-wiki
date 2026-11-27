# Datové řady a vzorce
## 1. Zadaní

Mějme tato naměřená data:

|čas (t)|naměřená data M|Konstanta 1|Konstanta 2|Průměr Konstant|S|
|:---:|:---:|:---:|:---:|:---:|:---:|
||3|||||
||5|||||
||6|||||
||7|||||
||9|||||
||11|||||
||13|||||
||14|||||
||17|||||
||18|||||

Úkolem je doplnit časovou řadu začínající v čase $2 \mathrm{s}$ s krokem $300 \mathrm{ms}$.

Dále, doplnit dvě konstanty, jedna roste z hodnoty 1 krokem 0,7, druhá klesala z hodnoty 3 krokem 0,25. 

Následně vypočítat průměr konstant.

V poslední části určit hodnoty S, která je rovna $S = \mathrm{průměr konstant} \cdot \cos(t*M)$. A výsledky zobrazit v grafu v závislosti na čase. 

### Návod:

Abychom doplnili lineární řadu, musíme napsat první dvě hodnoty, obě označíme a pomocí čtverečku vpravo dole dokážeme tuto řadu roztáhnout na požadovanou délku, nebo případně dvojitým kliknutím se řada roztáhne podél jiné řasdy (v našem případě by se tak roztáhla po číslo 18.)

Vzorce se doplňují do první buňky, začínají "=", hodnoty z jiných buněk se doplňují adresací, například "A2" znamená hodnotu z buňky A2. S tím jak vzorec budeme kopírovat do dalších buněk, adresa se bude automaticky posouvat. Například, mějme vzorec v buňce C2, který vypadá =A2+2, pokud vzorec zkopírujeme do buňky C3, vzorec se upraví na =A3+2. Pokud bychom nechtěli aby se toto stalo, lze takzvaně absolutně adresovat pomocí dolarových značek případně toto za nás udělá stisknutí F4, adresace tak bude vapadat takto $A$2. 

Graf následně vytvoříme pomocí označení nejdříve y hodnoty a následně x hodnoty v kartě vložení vybereme typ grafu, který se nejvíce hodí. 

## 2. Zadání

|datum|úhel $\alpha$ (°)|Konstanta 1|Konstanta 2|Průměr Konstant|S|
|:---:|:---:|:---:|:---:|:---:|:---:|
||0|||||
||30|||||
||60|||||
||90|||||
||120|||||
||150|||||

Sloupec datum vyplňte lineární řadou od data kdy úkol vyplňujete. Konstanty jsou stejné jako v předchozím zadání. Stejně tak jako průměr konstant. Hodnoty S následně dopočítat vzorcem $S = (Prumerkonstant + 2) \cdot \cos(\alpha)$. 

Hodnoty pak následně vyneste v závislosti na úhlu ve sloupcovém grafu.

## 3. Zadání

|Měsíc|$2 \cdot \pi$|Konstanta 1|Konstanta 2|Průměr Konstant|S|
|:---:|:---:|:---:|:---:|:---:|:---:|
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||

Sloupec s názvem "Měsíc" doplňte lineární řadou od ledna. Do sloupce "$2 \cdot \pi$" doplňte vzorcem hdonotu $2 \cdot \pi$, Konstanty jsou stejné, stejně jako jejich průměr. Hodnota S je zadaná vzorcem $S = 2\cdot \pi (Prumerkonstant)^2$. 

Hodnoty následně zobrazte ve sloupcovém grafu v závislosti na měsíci.








