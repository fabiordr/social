# Fabio Rigoli — Engenharia de Segurança do Trabalho

Landing page responsiva em português, desenvolvida com React, TypeScript, Vite e Tailwind CSS. Ilustração industrial original em SVG, movimento com o cursor, controle de animações e respeito a `prefers-reduced-motion`. Contato direto por WhatsApp e telefone; sem formulário ou backend.

## Desenvolvimento

Node.js 22 ou superior (validado com Node.js 24).

```sh
cd /workspace/social
npm ci
npm run dev -- --port 5173
```

```sh
npm run build
npm run preview -- --port 4173
```

A compilação gera `dist/`, que pode ser hospedado em um serviço de sites estáticos. Nenhum deploy foi realizado. Não são necessárias chaves, banco de dados, fontes externas ou serviços pagos. Use o checkout existente; não é necessário criar worktree.

## Conteúdo e contato

Dados fornecidos: Fabio Rigoli da Rosa; Engenheiro de Segurança do Trabalho; CREA PR-242308/D; +55 (49) 99132-0199. Textos, serviços, contato e componentes estão em `src/main.tsx`; estilos em `src/style.css`.

O escopo comercial sugerido inclui GRO/PGR, laudos e avaliações, ergonomia e consultoria em NRs. Cada contratação exige avaliação do enquadramento e da habilitação/escopo aplicáveis. O site não afirma que todas as empresas precisam dos mesmos documentos, não confunde LTCAT com PGR e não oferece PCMSO como entrega exclusiva do engenheiro.

## Pesquisa: limitação registrada

A consulta pública ao portal de Normas Regulamentadoras do Ministério do Trabalho e Emprego e ao site OnSafety foi bloqueada pelo proxy do ambiente (HTTP 403). Assim, não foi possível concluir a pesquisa de mercado solicitada nem validar atualizações normativas em fontes online. Não há estatísticas de mercado, depoimentos, clientes, certificações ou resultados inventados no site.

Fonte oficial a consultar antes de uso comercial: https://www.gov.br/trabalho-e-emprego/pt-br/assuntos/inspecao-do-trabalho/seguranca-e-saude-no-trabalho/ctpp-nrs/normas-regulamentadoras-nrs

Confirmar o portfólio efetivamente oferecido e revisar a aplicabilidade das normas às atividades atendidas. O site não afirma validação do registro no CREA.

## Validação realizada

- Compilação TypeScript e Vite.
- Chromium: navegação desktop e celular, menu móvel, acordeão de dúvidas, oito links de WhatsApp, controle de movimento e preferência por movimento reduzido.
- Verificação de ausência de erros JavaScript e de overflow horizontal.
