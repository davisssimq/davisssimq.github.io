# Automatické zálohování v Linuxu pomocí cron
## O projektu

Tento projekt ukazuje, jak v operačním systému **GNU/Linux** vytvořit jednoduchý systém automatického zálohování dat pomocí nástroje **cron** a Bash skriptu.
Cílem je naučit se:
- práci v Linux terminálu
- tvorbu jednoduchého shell skriptu
- plánování úloh pomocí cron
- automatizaci záloh dat

---

## Použité technologie

- GNU/Linux (Ubuntu / Debian)
- Bash (shell skript)
- cron (plánování úloh)
- tar (komprese dat)

---

## Jak to funguje

1. Vytvoří se složka s daty (`~/data`)
2. Skript vytvoří komprimovanou zálohu
3. Záloha se uloží do složky `~/backup`
4. Cron automaticky spouští skript v pravidelný čas
5. Vzniká log o každé záloze

---

# Instalace a nastavení

## 1️) Instalace cron
