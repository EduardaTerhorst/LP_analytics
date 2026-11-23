# LP Analytics — React MVP (frontend)

Protótipo React para centralizar gestão e análise de Landing Pages rastreadas. Interface em português, responsiva e pronta para evolução.

## Rodar localmente

1. Instale Node.js (versão LTS).
2. Abra a pasta no terminal.
3. Execute:

```bash
npm install
npm run dev
```

4. Abra o endereço local exibido pelo Vite.

## Build

```bash
npm run build
npm run preview
```

## O que está incluído
- Dashboard com métricas, gráficos e origem de tráfego (dados demonstrativos).
- Listagem e filtros por etapa, pesquisa por LP/campanha.
- Cadastro de LP (estado local durante a sessão; não persistido ainda).
- Detalhes de LP.
- Feed de eventos recentes de exemplo.
- Página de comportamento com visualização ilustrativa.
- Checklist demonstrativo para preparação/validação de HTML.
- Configurações e endpoint ilustrativo.
- Layout responsivo.

## O que ainda NÃO está conectado
- API/rota de recebimento de eventos no Nginx.
- Banco de dados e persistência.
- Tracker JavaScript real embutido nas LPs.
- Autenticação, permissões e proteção do dashboard.
- Integração/publicação RD Station.
- Validação real do HTML, consentimento e política de retenção.

Os dados da interface são exemplos fictícios e não representam tráfego real.

## Próximas etapas sugeridas
1. Definir backend, autenticação e banco.
2. Implementar registro/persistência de LPs e IDs.
3. Construir tracker universal e API de ingestão com validação, limites e controles antiabuso.
4. Testar a integração com a forma real de publicação do RD Station.
5. Implementar filtros e métricas com dados reais, exportação e privacidade/LGPD.
