# Onboarding Adiante · Materiais do Gerente Comercial Parceiro

Materiais publicados pelo GitHub Pages. Cada pasta é uma página.

| Pasta | Endereço | Uso |
|---|---|---|
| raiz | https://gibalara.github.io/onboardingadiante/ | Página de entrada com os 3 materiais |
| `jornada/` | https://gibalara.github.io/onboardingadiante/jornada/ | Enviado ao candidato |
| `playbook/` | https://gibalara.github.io/onboardingadiante/playbook/ | Enviado ao gerente após o contrato |
| `portal/` | https://gibalara.github.io/onboardingadiante/portal/ | Uso interno dos gestores |

## Ativar o GitHub Pages (uma vez)

Settings → Pages → Source: **Deploy from a branch** → Branch: **main** / **(root)** → Save.
O site fica no ar em 1 a 2 minutos e se atualiza a cada envio para o repositório.

## Como atualizar um material

1. Baixe o arquivo novo gerado no Claude: `jornada-github.html`, `playbook-github.html` ou `portal-github.html`.
2. Dê dois cliques no atalho `publicar-materiais-adiante` (Windows: .bat · Mac: .command).
3. O GitHub Pages publica em cerca de 1 minuto.

Sem o atalho: no GitHub, abra a pasta, clique em **Add file → Upload files**, envie o arquivo com o nome `index.html` e confirme o commit.

## Observações

- Não renomeie as pastas: os endereços dependem delas.
- No portal publicado fora do Claude, o registro e as configurações de administração ficam desativados.
- O arquivo `.nojekyll` evita processamento extra do GitHub Pages; não apague.
