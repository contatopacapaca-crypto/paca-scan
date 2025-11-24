# paca-scan

Projeto pronto para deploy na Vercel. Captura a geolocalização do usuário (após permissão) e envia para um chat do Telegram via função serverless.

## Como publicar

Opções:
1. **Upload direto na Vercel** (no painel escolha Upload project)
2. **Criar repositório no GitHub e conectar à Vercel**

### Variáveis de ambiente necessárias (no projeto Vercel > Settings > Environment Variables)
- BOT_TOKEN = seu token do bot (ex.: 123456789:AAH_xxx...)
- CHAT_ID = seu chat id (ex.: 5981527159)

### Observações de segurança
- Não exponha o BOT_TOKEN em arquivos públicos.
- Depois de configurar e testar, recomendo revogar o token usado e gerar um novo para segurança.

