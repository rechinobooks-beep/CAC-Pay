# CACP — Colégio Adventista da Chamba Platform

**Versão:** 0.2 Beta  
**Tipo:** Protótipo de apresentação  
**Idioma:** Português  
**Moeda demonstrativa:** Metical (MT)

## Objetivo

O CACP é um protótipo de interface para demonstrar como a secretaria do Colégio Adventista da Chamba poderá acompanhar alunos, mensalidades, pagamentos e recibos.

## Como executar

1. Abra `index.html` num navegador moderno.
2. No ecrã inicial, entre com qualquer identificador de demonstração não vazio.
3. Consulte os alunos e experimente adicionar um novo registo fictício.
4. Em **Mensalidades**, escolha o mês e o ano para ver estados demonstrativos.
5. Simule um pagamento e consulte o histórico.
6. Em **Recibos**, selecione o comprovativo e use **Imprimir / Guardar PDF**.

Não é necessário instalar dependências ou iniciar um servidor.

## Funcionalidades da Beta 0.2

- Ecrã inicial de acesso demonstrativo.
- Painel com indicadores de alunos e movimentos simulados.
- Lista de alunos com pesquisa e filtro por área.
- Formulário para adicionar alunos fictícios durante a sessão.
- Consulta do estado das mensalidades por mês e ano.
- Registo simulado de pagamento por transferência ou cartão.
- Histórico de pagamentos com referência, valor e data.
- Geração e impressão de recibos demonstrativos.
- Interface adaptável a computador, tablet e telemóvel.

## Dados e limitações

A interface começa com sete registos inteiramente fictícios. Os dados criados durante a utilização existem apenas na memória da página e são perdidos ao atualizar ou fechar o navegador.

**Esta versão não é um sistema financeiro em produção.** O ecrã de entrada não é autenticação: não valida palavra-passe nem protege o conteúdo. Também não possui:
- backend, base de dados central ou cópias de segurança;
- autenticação segura, sessões ou gestão de permissões;
- integração com bancos, cartões ou gateways;
- confirmação automática de transferências;
- emissão fiscal ou recibos oficiais;
- notificações por SMS, email ou WhatsApp;
- auditoria financeira ou trilho de alterações de produção.

Os pagamentos são apenas simulações locais. Nenhum dinheiro é movimentado. Os recibos são explicitamente identificados como fictícios e não confirmam recebimento bancário.

## Próximas etapas antes de um piloto real

1. Obter autorização formal da direção para o projeto e uso do nome/identidade da escola.
2. Definir requisitos com a direção, secretaria, encarregados e responsáveis técnicos.
3. Implementar backend, base de dados protegida e autenticação segura.
4. Definir perfis e permissões (encarregado, secretaria, direção e administrador).
5. Integrar um fornecedor de pagamentos autorizado, após validação contratual e regulatória em Moçambique.
6. Implementar conciliação bancária e confirmação de pagamentos.
7. Definir recibos oficiais com a escola e validar requisitos fiscais/contabilísticos.
8. Realizar testes de segurança, privacidade, recuperação e acessibilidade.

## Privacidade

Não inserir dados pessoais reais de alunos, encarregados ou funcionários neste repositório público. Para testes com dados reais, utilizar um ambiente privado, acesso restrito, autorização institucional e medidas adequadas de proteção de dados. Como os estudantes podem ser menores, os testes devem ser supervisionados pela escola e pelos adultos responsáveis.

---
**CACP Beta 0.2 — protótipo não oficial, para discussão e demonstração.**
