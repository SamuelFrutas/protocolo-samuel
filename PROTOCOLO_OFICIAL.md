# PROTOCOLO DE DESENVOLVIMENTO — SAMUEL
Versão 2.0 — 23/11/2026

Este protocolo define um fluxo simples para transformar as ideias de Samuel em sistemas funcionais. Deve ser consultado no início de cada novo trabalho.

## 1. Conversa e definição da ideia
- Samuel começa conversando sobre a ideia, explicando o que deseja e dando sugestões.
- O assistente deve ouvir, organizar os requisitos e ajudar a definir o funcionamento do sistema.
- Não começar a programar o sistema definitivo antes de apresentar e receber aprovação do protótipo.
- Fazer somente as perguntas indispensáveis para entender o que Samuel quer. Não complicar o planejamento.

## 2. Primeiro passo: protótipo funcional
- Criar primeiro um protótipo web navegável no repositório central `SamuelFrutas/samuel-prototipos`, em uma pasta própria para o projeto.
- Usar GitHub Pages ou outra forma simples de disponibilizar um link acessível para Samuel.
- O protótipo deve apresentar as telas, navegação e principais interações do sistema.
- Quando houver dados, utilizar o armazenamento do próprio navegador: `localStorage` ou `IndexedDB`. Não confundir isso com `localhost`, que é um endereço de servidor.
- Permitir experimentar os fluxos de verdade: cadastrar, editar, excluir, consultar e outras ações previstas para o protótipo.
- Os dados devem continuar salvos ao atualizar ou reabrir a página no mesmo navegador.
- Usar dados fictícios para demonstração. Não exigir banco de dados ou backend definitivo nessa fase.
- Entregar o link para Samuel avaliar e ajustar o protótipo conforme as orientações dele.
- **Só iniciar o desenvolvimento definitivo depois que Samuel aprovar explicitamente o protótipo.**

## 3. Depois da aprovação: planejamento do desenvolvimento
- Com o protótipo aprovado, organizar o desenvolvimento em etapas numeradas, da primeira até a conclusão.
- Cada etapa deve dizer de forma simples o que será feito e qual resultado será entregue.
- Apresentar o plano completo para Samuel saber o caminho até o sistema ficar pronto.
- Registrar o plano e o andamento em um arquivo simples no repositório do projeto, para não perder a continuidade entre conversas.
- Não inventar etapas burocráticas nem incluir tarefas que não contribuam para entregar o sistema.

## 4. Execução por etapas
- Samuel decide qual etapa quer executar. O assistente deve realizar a etapa solicitada e entregar o resultado antes de passar para outra.
- Ao concluir uma etapa, informar objetivamente o que foi feito, o que ficou pendente e qual é a próxima etapa do plano.
- Preservar o que já foi aprovado e implementado. Não refazer partes prontas sem necessidade ou autorização.
- Se surgir uma ideia nova, conversar com Samuel e encaixá-la no plano sem perder o andamento atual.
- Fazer apenas os testes necessários para confirmar que a etapa funciona. Corrigir problemas encontrados, mas não ficar repetindo auditorias, testes ou verificações sem necessidade e sem avanço real.
- Não declarar concluído algo que não foi entregue. Se houver impedimento real, explicar diretamente qual é e o que falta para resolvê-lo.

## 5. Botão de continuidade obrigatório
- Sempre que houver uma próxima etapa ou ação pendente, terminar a resposta com um botão clicável.
- O botão deve conter um comando claro e pronto para Samuel iniciar a próxima etapa sem precisar escrever novamente.
- O comando deve respeitar a ordem do planejamento e identificar o projeto e a etapa correta.
- Depois de executar a etapa solicitada, atualizar o andamento e apresentar o botão para a etapa seguinte.
- Não mostrar botão quando o projeto estiver concluído ou não houver uma próxima ação definida.

## 6. Entrega e publicação
- Priorizar entregas que Samuel consiga abrir e utilizar, com link para o protótipo ou versão de avaliação sempre que disponível.
- Informar claramente se o link é do protótipo, de uma versão de testes ou do sistema em produção.
- Não publicar em produção nem realizar ações que afetem usuários reais sem autorização expressa de Samuel.

## 7. Regra principal
**Ouvir a ideia. Criar o protótipo funcional com armazenamento no navegador. Aguardar aprovação. Planejar o desenvolvimento em etapas. Executar uma etapa por vez, entregar e deixar o botão para continuar. O objetivo é concluir o sistema, sem burocracia e sem testes intermináveis.**
