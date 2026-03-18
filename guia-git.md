# Guia Git – DevMarket

## Fluxo de trabalho
- `git status` → ver o que mudou
- `git add .` → staging area
- `git commit -m "msg"` → salvar snapshot
- `git push` → enviar ao GitHub
- `git log --oneline` → ver histórico

## Comandos de reversão
- `git checkout <hash>` → visitar versão anterior
- `git revert HEAD` → desfazer com segurança ✅
- `git reset --hard` → ⚠️ perigoso, só local!
