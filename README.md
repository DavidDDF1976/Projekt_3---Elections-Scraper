# Projekt_3---Elections-Scraper

Elections Scraper Projekt
Třetí projekt pro akademii engeto.

Popis Projektu
Tento projekt slouží pro extrahování výsledků z parlamentních voleb v roce 2017.Odkaz k prohlédnutí zde: https://volby.cz/pls/ps2017nss/ps3?xjazyk=CZ

Instalace knihoven
Knihovny, které jsou použity v kódu jsou uložené v souboru requirements.txt.Pro instalaci doporučuji použít nové virtuální prostředí a s nainstalovaným manažerem spustit následovně:

pip --version #ověření verze manažeru pip install -r requirements.txt #instalace knihoven

Spuštění projektu
Spuštění souboru projekt_3.py v rámci příkaz. řádku požaduje dva povinné argumenty.

projekt_3.py "odkaz-uzemniho-celku" "nazev-vysledneho-souboru"

Následně se vám stáhnou výsledku jako soubor s připonou .csv.

Ukázka projektu
Výsledky hlasování pro okres Prostějov:

1. argument: https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103
2. argument: results_prostejov.csv

Částečný výstup:

code,location,registered,envelopes,valid,Občanská demokratická strana,Řád národa - Vlastenecká unie,CESTA ODPOVĚDNÉ SPOLEČNOSTI,Česká str.sociálně demokrat.,Radostné Česko,STAROSTOVÉ A NEZÁVISLÍ,Komunistická str.Čech a Moravy,Strana zelených,"ROZUMNÍ-stop migraci,diktát.EU",Strana svobodných občanů,Blok proti islam.-Obran.domova,Občanská demokratická aliance,Česká pirátská strana,Referendum o Evropské unii,TOP 09,ANO 2011,Dobrá volba 2016,SPR-Republ.str.Čsl. M.Sládka,Křesť.demokr.unie-Čs.str.lid.,Česká strana národně sociální,REALISTÉ,SPORTOVCI,Dělnic.str.sociální spravedl.,Svob.a př.dem.-T.Okamura (SPD),Strana Práv Občanů
506761,Alojzov,205,145,144,29,0,0,9,0,5,17,4,1,1,0,0,18,0,5,32,0,0,6,0,0,1,1,15,0
