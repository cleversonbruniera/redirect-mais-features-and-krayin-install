# Redirect+ (agora Nandu) - Funcionalidades e Documentação

**Nota importante:** Redirect+ é um produto proprietário (agora rebranded como Nandu). Não há código-fonte público ou repositório GitHub oficial com licença MIT. As funcionalidades abaixo foram extraídas da documentação oficial e site.

## Funcionalidades Principais (Gestão de Grupos e Administração)

- Criação automática de grupos e comunidades do WhatsApp
- Agendamento de mensagens (texto, áudio, vídeo, enquetes, links)
- Menção em massa de participantes
- Redirecionamento automatizado de leads baseado em quantidade de pessoas nos grupos
- Troca de títulos de grupos em massa
- Alteração de permissões de fala (anúncio vs todos)
- Importação/exportação de grupos (links)
- Remoção de leads duplicados
- Finalização de grupos e remoção de participantes em massa
- Lista de bloqueio (blacklist) para remover números específicos
- Mensagens de entrada e saída de grupos (privadas para leads)
- Aquecimento de chip/conta WhatsApp
- Múltiplas instâncias (celulares principais e auxiliares)
- Campanhas com estratégias de distribuição
- Integrações com plataformas de vendas (Hotmart, Eduzz, Kiwify, etc.)
- Pixel, Tag Manager e Analytics
- Spintax para variação de mensagens
- Contabilização de cliques em links
- Redirecionador por clique / atendimento em rodízio

## Links Oficiais
- Site: https://www.redirectmais.com.br/ (agora Nandu)
- Central de Ajuda: https://redirectmais.gitbook.io/central-de-ajuda/

## Alternativas Open Source MIT (para pular a fase proprietária)

Não existe um clone 1:1 do Redirect+ em MIT, mas estas bibliotecas/projetos cobrem as funcionalidades de administração de grupos:

1. **Baileys** (WhiskeySockets/Baileys) - MIT
   - API WebSocket para WhatsApp Web
   - Criação de grupos, adicionar/remover participantes, promover admins, mudar nome/descrição/configurações, links de convite
   - https://github.com/WhiskeySockets/Baileys

2. **Levix** (Abdodiab2005/levix) - MIT
   - Bot self-hosted com 55 comandos, moderação de grupos, mensagens agendadas, painel web
   - https://github.com/Abdodiab2005/levix

3. **WA-AKG** (mrifqidaffaaditya/WA-AKG) - MIT
   - Gateway multi-sessão com Next.js + Baileys + Prisma, dashboard, webhooks, n8n
   - https://github.com/mrifqidaffaaditya/WA-AKG

4. **WPPConnect** (wppconnect-team) - MIT (verificar licença por repo)
   - Biblioteca e servidor para automação de WhatsApp Web
   - https://github.com/wppconnect-team

5. **whatsapp-redirect** (danilovilhena/whatsapp-redirect) - MIT
   - API simples para organizar e redirecionar para grupos em lançamentos
   - https://github.com/danilovilhena/whatsapp-redirect

Use Baileys como base para construir a lógica de administração de grupos que o Redirect+ oferece.