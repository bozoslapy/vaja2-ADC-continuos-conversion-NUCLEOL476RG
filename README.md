# vaja2-ADC-continuos-conversion-NUCLEOL476RG
A) Glede na vašo razvojno ploščico izberite ustrezni analogni vhod. Kateri pin ste določili?
--> PC0

B) Povežite potenciometer na vaš ustrezni kanal/pin. Na zaslonu obkljukate izbrani pin (ADC…); usterzno se vam mora pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina?
--> ADC_IN1

C) V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16 MHz. (potrdite z ENTER) Kaj opazite?

-->vidimo da se :
          --> FCLK spremeni na 64 MHz
          --> HCLK spremeni na 64 MHz
          --> APB2 spremeni na 64 MHz
          --> APB1 timer pa na 32 MHz
          --> vsi so imeli začetno vrednostn 80 MHz

Č) Clock Prescaler nastavimo z deliteljem 4. Kolikšna je sedaj preskalirana frekvenca takta fpreskalirana? 

--> 16 MHz

D) Sampling time (čas vzorčenja tvz_ciklih) spremenite na 239.5 cikov. Pravi čas vzorčenja se nato poveča še za 12 ciklov. Koliko znaša pravi čas vzorčenja tvz v mikro sekundah?

fpreskalirana = 16 MHz
tvz_ciklih = 239,5 ciklov

----------------------------------

čas vzročanja = ?

čas vzročanja = tvz_ciklih / fpreskalirana
čas vzročanja = 239,5 ciklov / 16 MHz
čas vzročanja = 14,97 ms
