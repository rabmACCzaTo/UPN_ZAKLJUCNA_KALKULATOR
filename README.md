# UPN_ZAKLJUCNA_KALKULATOR

Na začetku kalkulator deluje v privzeti operaciji, na primer seštevanje (+). Na LCD zaslonu je prikazana trenutno izbrana operacija in osnovno sporočilo, ki uporabnika obvešča, kako vnesti podatke.
Uporabnik vnaša številke preko 3x4 tipkovnice (keypad). Vnesena števila se prikazujejo na LCD zaslonu – najprej prvo število, nato po potrditvi (s tipko *) drugo število.
Pred ali po vnosu števil lahko uporabnik pritisne poseben fizični gumb, ki zamenja trenutno matematično operacijo. Vsak pritisk tega gumba preklopi kalkulator med operacijami v naslednjem vrstnem redu:
seštevanje (+) → odštevanje (−) → množenje (×) → deljenje (÷) → nato znova seštevanje (+) in tako naprej v krogu.
Vsakič, ko se operacija spremeni, se nova izbrana operacija prikaže na LCD zaslonu, da uporabnik ve, katera bo uporabljena.
Ko sta vnešeni obe števili, uporabnik pritisne tipko *, s katero potrdi izračun. Kalkulator izvede izračun z izbrano operacijo in rezultat se prikaže na LCD zaslonu.
Če želi uporabnik začeti znova, pritisne tipko #, s katero se:
izbriše vnesena števila in rezultat,
ponastavi operacija na privzeto (seštevanje),
in LCD se očisti ter prikaže začetno stanje.
Kalkulator je tako pripravljen za nov izračun.


KOSOVINA(Potrebni elementi):

| **#** | **Element**                 | **Količina** | **Opombe**                         |
| ----: | --------------------------- | -----------: | ---------------------------------- |
|     1 | Arduino Uno                 |            1 | Mikrokontrolerska plošča           |
|     2 | 16x2 LCD zaslon             |            1 | Zaslon s 16 stolpci in 2 vrsticama |
|     3 | Potenciometer               |            1 | Za prilagajanje kontrasta LCD      |
|     4 | Gumb (tipka)                |            1 | Enostavna vhodna naprava           |
|     5 | Upor 220 Ω                  |            2 | Za zaščito gumbov ali LED          |
|     6 | 3x4 Keypad (tipkovnica)     |            1 | Tipkovnica z 12 tipkami            |
|     7 | Žice za povezavo (jumperji) |           27 | Moški-moški ali moški-ženski       |


SLIKA VEZAVE:

![UPNSLIKA](https://github.com/user-attachments/assets/e2feb750-b9b9-4d75-9217-6083d0aa5040)


SLIKA SHEME:



VIDEO:

https://github.com/user-attachments/assets/a69c2b54-24c3-4843-a131-6b40876c77b1

