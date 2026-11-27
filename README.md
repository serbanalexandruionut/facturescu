# Facturescu

Program de facturare **gratuit** pentru Windows și Mac, cu trimitere în **RO e-Factura** din SPV-ul firmei tale.

- facturi și storno, plătitori și neplătitori de TVA, cote 21%, 11%, 0%;
- verificare la validatorul ANAF înainte de emitere;
- trimitere automată în SPV, starea facturilor și arhiva semnată de ANAF;
- facturile primite de la furnizori, aduse din SPV;
- chitanțe cu suma în litere;
- export lunar pentru contabil (PDF, XML, registre pentru Excel);
- mai multe firme în același program, fiecare cu facturile și documentele ei;
- logo-ul firmei și trei modele de factură (Clasic, Modern, Compact), cu previzualizare;
- catalog de produse cu cod CPV din lista oficială, trimis în XML-ul e-Factura.

Datele rămân pe calculatorul tău. Facturile nu trec prin serverele noastre.

## Conectarea la SPV, o singură dată

1. Îți faci cont pe [www.anaf.ro/InregOauth/](https://www.anaf.ro/InregOauth/) (cu „/” la final), îl activezi din e-mailul de la ANAF și te loghezi cu utilizatorul și parola.
2. La **Editare profil Oauth** completezi: denumire `Facturescu`, Callback URL `https://localhost/facturescu-anaf`, serviciu **E-Factura**, apoi apeși **Generare Client ID**.
3. Copiezi Client ID și Client Secret în Facturescu, la Setări → Conectare SPV.
4. **Aștepți 10 minute**, până activează ANAF aplicația. Altfel conectarea dă eroarea „access_denied”.
5. Introduci tokenul, apeși **Conectează** și alegi certificatul firmei.

Programul te ghidează pas cu pas.

## Descărcare

Descarcă Facturescu de pe **[antreprenorilor.ro/facturescu](https://antreprenorilor.ro/facturescu)**.

Folosirea programului înseamnă acceptarea [termenilor de utilizare](https://antreprenorilor.ro/facturescu/termeni): folosire liberă și gratuită, program oferit „așa cum este”, fără garanții.

---

Facturescu este oferit de SAI GRUP INT SRL prin [Antreprenorilor.ro](https://antreprenorilor.ro).
