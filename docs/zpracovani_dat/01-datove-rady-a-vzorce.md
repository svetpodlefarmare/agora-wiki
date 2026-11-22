Při zpracování dat se nám hodí občas dodat předem dano udatovou řadu. Může se jednat o měsíce v roce nebo dny v týdnu. Často si také budeme muset dodat čadu lineárně rostoucích čísel. Například, dostaneme-li řadu čísel a víme že se jedná o hodnoty v závislosti na jiné řadě. 
Ta nám ale nebyla dána, tudíž si ji musíme připravit abychom například mohli data zobrazit. Představme si příklad:

Mějme 

|čas (t)|naměřená data|
|:---:|:---:|
||3|
||5|
||6|
||7|
||9|
||11|
||13|
||14|
||17|
||18|

naměřená data z nějakého senzoru ši z jiného zdroje. Ale nemáme jednotlivé časy, jen víme že meření proběhlo každých $300 \mathrm{ms}$ a začínalo v čase $2 \mathrm{s}$. Tabulku si můžeme tak doplnit pro další zpracování. 

Pomocí vzorců v buňkách tak můžeme dopočítat různé další hodnoty a dohledat a případně tak zobrazit další závislosti. Pokračujme tedy v našem příkladu. Víme tedy

|čas (t)|naměřená data|
|:---:|:---:|
|2  |3|
|2,3|5|
|2,6|6|
|2,9|7|
|3,2|9|
|3,5|11|
|3,8|13|
|4,1|14|
|4,4|17|
|4,7|18|

a teké lze z našich dat urči jiné hodnoty, například hodnotu označenou K, která je rovna $K = čas \cdot naměřená \. data$


