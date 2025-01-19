Ovaj projekt implementira **Conway's Game of Life** koristeći **Common Lisp** za logiku simulacije i **HTML/CSS/JavaScript** za izradu grafičkog sučelja. **Game of Life** je matematički model temeljen na jednostavnim pravilima koja upravljaju životom i smrću ćelija u mreži. Korištenjem ovog projekta korisnici mogu pratiti evoluciju stanica kroz generacije, kontrolirati brzinu simulacije i vizualizirati dinamiku igre.

## Sadržaj datoteka

- **gol.lisp**: Implementacija logike igre u **Common Lisp**.
- **ui.lisp**: Sučelje i funkcionalnosti povezane s korisničkom interakcijom u **Common Lisp**.
- **index.html**: Osnovna HTML stranica koja prikazuje igru i omogućuje korisničku interakciju.
- **package.lisp**: Definicija paketa za organizaciju Lisp koda.
- **README.md**: Ovaj dokument s osnovnim informacijama o projektu.

## Postavke za pokretanje

### Preduvjeti

Za pokretanje ovog projekta trebate imati instaliran:

- **SBCL (Steel Bank Common Lisp)**: Kompajler za **Common Lisp**.
- **Visual Studio Code**: Preporučeni editor za razvoj uz instalirane ekstenzije za **Lisp** (npr. **SLIME**).
- Web preglednik za pokretanje **HTML** i **JavaScript** dijela.

### Instalacija

1. **Klonirajte projekt**:
   ```bash
   git clone <repo_url>
2. **Pokrenite Lisp aplikaciju**:
    Otvorite terminal i pokrenite SBCL:
        sbcl
    Učitajte i pokrenite Lisp kod:
        (load "gol.lisp")
3. **Pokrenite web aplikaciju:**:
    Otvorite index.html u svom web pregledniku, ili pomoću Live server ekstenzije u Visual Studio Code
    Igra će biti prikazana, a korisnici mogu interaktivno upravljati simulacijom.
