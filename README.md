# vaja2-ADC-continuos-conversion-NUCLEOL476RG
b) Glede na vašo razvojno ploščico izberite ustrezni analogni vhod. Kateri pin ste določili?
--> PC0

e) Povežite potenciometer na vaš ustrezni kanal/pin. Na zaslonu obkljukate izbrani pin (ADC…); usterzno se vam mora pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina?
--> ADC_IN1

f) V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16 MHz. (potrdite z ENTER) Kaj opazite?

-->vidimo da se :
          --> FCLK spremeni na 64 MHz
          --> HCLK spremeni na 64 MHz
          --> APB2 spremeni na 64 MHz
          --> APB1 timer pa na 32 MHz
          --> vsi so imeli začetno vrednostn 80 MHz

h) Clock Prescaler nastavimo z deliteljem 4. Kolikšna je sedaj preskalirana frekvenca takta fpreskalirana? 
--> 16 MHz


j) Sampling time (čas vzorčenja tvz_ciklih) spremenite na 239.5 cikov. Pravi čas vzorčenja se nato poveča še za 12 ciklov. Koliko znaša pravi čas vzorčenja tvz v mikro sekundah?

(enačba: tvz=tvz_ciklih/fpreskalriana)? ______________________________ 
