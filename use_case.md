# UC-ALZA-001 Prihlásenie používateľa

## Vstupná podmienka
Používateľ má otvorenú hlavnú stránku Alza.sk v internetovom prehliadači.

## Aktéri
- Používateľ (registrovaný zákazník)

## Základná postupnosť
1. Používateľ klikne na tlačidlo **„Prihlásiť“** v hornej časti stránky.
2. Systém zobrazí prihlasovací formulár s políčkami pre **e-mail/ID používateľa** a **heslo**.
3. Používateľ zadá platný e-mail a heslo.
4. Používateľ klikne na tlačidlo **„Prihlásiť“**.
5. Systém overí prihlasovacie údaje:
   - Ak sú údaje správne, používateľ je presmerovaný na svoj osobný účet / dashboard a zobrazuje sa jeho meno.

## Alternatívna postupnosť 1 – nesprávne údaje
1. Používateľ zadá nesprávny e-mail alebo heslo.
2. Systém zobrazí chybovú správu: **„Nesprávne prihlasovacie údaje“**.
3. Používateľ môže zvoliť možnosť **Obnoviť heslo** alebo opraviť údaje a skúsiť znova.

## Alternatívna postupnosť 2 – prázdne polia
1. Používateľ klikne na **„Prihlásiť“** bez vyplnenia e-mailu alebo hesla.
2. Systém zobrazí validačnú správu: **„Prosím, vyplňte e-mail a heslo“**.

## Poznámky
- E-mail musí byť platne formátovaný (napr. `meno@domena.sk`).
- Heslo musí spĺňať minimálne bezpečnostné pravidlá nastavené Alza.sk.
- Pri 3 po sebe idúcich neúspešných pokusoch môže systém dočasne zablokovať prihlásenie.
