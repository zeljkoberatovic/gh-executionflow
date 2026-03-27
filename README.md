# CI/CD Demo App (GitHub Actions)

Ovo je demo React aplikacija napravljena za vjezbanje CI/CD procesa kroz GitHub Actions.

## Sta je uradjeno kroz Actions

- Pokretanje workflowa na `push` i `workflow_dispatch`
- Podjela pipeline-a na jobove: lint, test, build i deploy
- Caching zavisnosti preko `actions/cache`
- Upload/download build i test artefakata (`upload-artifact`, `download-artifact`)
- Reusable workflow (`workflow_call`) za deploy korak
- Matrix build (vise Node verzija i OS kombinacija)
- Conditional koraci (`if: failure()`) i report job

## Namjena

Projekat je iskljucivo edukativni demo i koristi se za vjezbanje CI/CD koncepata u GitHub Actions.
