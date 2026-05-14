# The Forge Release Notes

Public release notes for The Forge - versione 1.1.2

**Repository GitHub:** https://github.com/unkredible/the-forge-release-notes

**GitHub Pages (URL pubblica):** https://unkredible.github.io/the-forge-release-notes/

⚠️ **IMPORTANTE - Restrizioni Release:** Non fare release per macOS e Linux fino a nuova indicazione. Solo Windows è abilitato per il release.

## Struttura

- Repository locale: `c:\git\the-forge-release-notes`
- File versioni: `v1.0.0.md`, `v1.0.1.md`, `v1.1.0.md`, `v1.1.2.md`, etc.
- File principale: `v1.1.2.md` (versione corrente)

## Come aggiornare le Release Notes

**⚠️ REGOLA IMPORTANTE: Ogni versione ha il suo file separato. NON sovrascrivere versioni precedenti.**

Quando rilasci una nuova versione di The Forge:

1. **Crea UN NUOVO file per la versione** (es. `v1.1.1.md`):
   - File deve seguire il formato: `v{major}.{minor}.{patch}.md`
   - Aggiungi le nuove feature sotto `## Added`
   - Documenta i cambiamenti sotto `## Changed`
   - Nota eventuali fix sotto `## Fixed`
   - Includi la data di release: `Release date: YYYY-MM-DD`

2. **Fai commit dei cambiamenti**:
   ```powershell
   cd c:\git\the-forge-release-notes
   git add v1.1.1.md
   git commit -m "Add v1.1.1 release notes: [descrizione feature]"
   ```

3. **Fai push su GitHub**:
   ```powershell
   git push origin main
   ```

4. Le modifiche appariranno automaticamente su GitHub Pages (https://unkredible.github.io/the-forge-release-notes/)

**Esempio:** Se stai aggiornando da 1.1.0 a 1.1.1:
- v1.1.0.md rimane intatto e inalterato
- Crea il nuovo file v1.1.1.md con i cambiamenti di questa release

## Nota sulla sincronizzazione

Il codice principale è nel repository `the-forge` (https://github.com/unkredible/the-forge), mentre questo repository contiene solo la documentazione pubblica dei release notes. Assicurati di aggiornare ENTRAMBI i repository quando fai un release:

1. Fai push del codice su `the-forge`
2. Aggiorna e fai push dei release notes su `the-forge-release-notes`
