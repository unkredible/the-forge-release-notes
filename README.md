# The Forge Release Notes

Public release notes for The Forge - versione 1.1.0

**Repository GitHub:** https://github.com/unkredible/the-forge-release-notes

**GitHub Pages (URL pubblica):** https://unkredible.github.io/the-forge-release-notes/

## Struttura

- Repository locale: `c:\git\the-forge-release-notes`
- File versioni: `v1.0.0.md`, `v1.0.1.md`, etc.
- File principale: `v1.1.0.md` (versione corrente)

## Come aggiornare le Release Notes

Quando rilasci una nuova versione di The Forge:

1. **Modifica il file della versione** (es. `v1.1.0.md`):
   - Aggiungi le nuove feature sotto `## Added`
   - Documenta i cambiamenti sotto `## Changed`
   - Nota eventuali fix sotto `## Fixed`

2. **Fai commit dei cambiamenti**:
   ```powershell
   cd c:\git\the-forge-release-notes
   git add v1.1.0.md
   git commit -m "Update v1.1.0 release notes: [descrizione change]"
   ```

3. **Fai push su GitHub**:
   ```powershell
   git push origin main
   ```

4. Le modifiche appariranno automaticamente su GitHub Pages (https://unkredible.github.io/the-forge-release-notes/)

## Nota sulla sincronizzazione

Il codice principale è nel repository `the-forge` (https://github.com/unkredible/the-forge), mentre questo repository contiene solo la documentazione pubblica dei release notes. Assicurati di aggiornare ENTRAMBI i repository quando fai un release:

1. Fai push del codice su `the-forge`
2. Aggiorna e fai push dei release notes su `the-forge-release-notes`
