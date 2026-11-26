# KI-resultater – Kuben VGS

Felles repo for kurset *KI-basert utvikling*. Her samler vi resultatene fra uke 3 og prosjektene fra uke 4 og 5.

Du har ikke skrivetilgang hit. Du legger inn filene dine med **fork** og **pull request**.

## Mapper

| Mappe | Innhold |
|-------|---------|
| `uke3/dittgithubnavn/` | `RESULTAT.md` (vinterdekk), `losning.html` og `README.md` (eksamen) |
| `prosjekter/dittgithubnavn.md` | Lenke og kort beskrivelse av prosjektet ditt |

**Endre bare dine egne filer.** Da får ingen konflikter.

## Slik gjør du det

```powershell
cd utvikling                                      # ved siden av sandbox-prosjekt – ikke inne i den
gh repo fork algebradamen/ki-resultater --clone
cd ki-resultater
# lag mappen eller filen din og kopier inn filene
git add .
git commit -m "Uke 3: resultater fra dittgithubnavn"
git push
gh pr create --fill
```

Har det kommet nye filer siden du forket? Trykk **Sync fork** på github.com, og kjør `git pull`.

## Mal for prosjekter/dittgithubnavn.md

```markdown
## Navn på prosjektet
- Laget av: Ditt Navn
- Prøv den: https://dittnavn.github.io/reponavn/
- Kode: https://github.com/dittnavn/reponavn
- Kort om: Én eller to setninger om hva den gjør, og for hvem.
```

---
© [algebradamen](https://github.com/algebradamen)
