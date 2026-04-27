# prompt-playbooks-for-teams

Kolekce prompt workflow které opakovaně používám — strukturované vstupy, kontrolní body, očekávaný výstup.

## O repozitáři

Jeden dobrý prompt nestačí. Pokud má AI šetřit čas opakovaně, potřebuju mít celý postup zdokumentovaný — co na vstupu, v jakém pořadí promptovat, kde je potřeba lidský pohled před dalším krokem. Tyhle playbooks jsou to co mi funguje pro konkrétní opakující se úkoly.

Každý playbook verzuju jako kód a testuju sadu vstupů pokaždé než změním prompt. Bez toho opravení jednoho problému vytvoří regresi někde jinde.

## Playbooks

- `playbooks/marketing-linkedin.md` — příprava LinkedIn příspěvků z podkladů
- `playbooks/product-interview-summary.md` — shrnutí uživatelských rozhovorů
- `playbooks/leadership-decision-memo.md` — strukturování rozhodovacích podkladů

## Struktura každého playbooku

- cíl workflow
- požadované vstupy
- sekvence promptů
- kontrolní bod před pokračováním
- očekávaný výstup

## License

MIT — viz LICENSE
