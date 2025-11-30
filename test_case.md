# Testovacie prípady – Prihlásenie používateľa

| ID | Popis | Testovacie kroky | Očakávaný výsledok |
|------------|-------|-------|------------------|
| TC-ALZA-001 | Prihlásenie s platnými údajmi | 1. Kliknúť na tlačidlo **„Prihlásiť“**.<br>2. Zadať platný e-mail a heslo.<br>3. Kliknúť na **„Prihlásiť“**. | Používateľ je presmerovaný na dashboard a zobrazuje sa jeho meno. |
| TC-ALZA-002 | Prihlásenie s nesprávnym e-mailom alebo heslom | 1. Kliknúť na tlačidlo **„Prihlásiť“**.<br>2. Zadať nesprávny e-mail alebo heslo.<br>3. Kliknúť na **„Prihlásiť“**. | Zobrazí sa chybová správa **„Nesprávne prihlasovacie údaje“**. Používateľ môže opraviť údaje alebo obnoviť heslo. |
| TC-ALZA-003 | Prihlásenie s prázdnymi poľami | 1. Kliknúť na tlačidlo **„Prihlásiť“** bez zadania údajov. | Zobrazí sa validačná správa **„Prosím, vyplňte e-mail a heslo“**. |
| TC-ALZA-004 | Dočasné zablokovanie po 3 neúspešných pokusoch | 1. Kliknúť na tlačidlo **„Prihlásiť“**.<br>2. Zadať nesprávny e-mail alebo heslo 3x po sebe. | Systém dočasne zablokuje možnosť prihlásenia a zobrazí príslušnú správu. |
