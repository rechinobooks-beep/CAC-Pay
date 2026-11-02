# CACP — Colégio Adventista da Chamba Platform

**Versão:** 0.1 Beta  
**Tipo:** Protótipo de apresentação  
**Idioma:** Português  
**Moeda demonstrativa:** Metical (MT)

## Objetivo

O CACP é um protótipo de interface para apoiar a gestão de mensalidades do Colégio Adventista da Chamba. Esta versão permite demonstrar a organização de alunos, o registo simulado de pagamentos e a apresentação de recibos demonstrativos.

## Como executar

1. Abra `index.html` num navegador moderno.
2. Navegue pelo menu lateral.
3. Consulte os alunos de demonstração.
4. Em **Mensalidades**, simule um registo.
5. Em **Recibos**, escolha o comprovativo e use **Imprimir / Guardar PDF**.

Não é necessário instalar dependências ou iniciar um servidor.

## Dados de demonstração

A interface contém sete registos inteiramente fictícios, todos na 11.ª classe, distribuídos pelas áreas A, B e C. Os números de aluno reproduzem apenas a estrutura solicitada para o teste, mas os nomes reais foram substituídos por identificadores genéricos para proteger a privacidade de estudantes.

## Funcionalidades incluídas

- Painel administrativo com indicadores demonstrativos.
- Lista de alunos com pesquisa e filtro por área.
- Formulário de registo simulado de mensalidades.
- Histórico local de movimentos da sessão.
- Geração visual de recibo demonstrativo.
- Impressão do recibo ou gravação em PDF pelo navegador.
- Layout adaptável a computador, tablet e telemóvel.

## Limitações — não utilizar para cobranças reais

Esta versão **não** é um sistema financeiro em produção. Não possui:
- autenticação real ou gestão de permissões;
- base de dados central ou cópias de segurança;
- integração com bancos, cartões ou gateways;
- confirmação automática de transferências;
- emissão fiscal ou recibos oficiais;
- notificações por SMS, email ou WhatsApp;
- auditoria financeira de produção.

Os botões de simulação apenas atualizam dados em memória no navegador. Os recibos estão explicitamente marcados como fictícios.

## Próximas etapas antes de um piloto real

1. Obter autorização formal da direção do colégio para o projeto e uso do nome/identidade.
2. Definir requisitos com a secretaria e a direção.
3. Implementar autenticação segura e perfis (encarregado, secretaria, direção e administrador).
4. Criar backend e base de dados protegida, com controlo de acesso por escola e por função.
5. Integrar um fornecedor de pagamentos autorizado, após validação contratual e regulatória em Moçambique.
6. Implementar conciliação bancária e confirmação de pagamentos por notificações assinadas do fornecedor.
7. Definir recibos oficiais com a escola e validar requisitos fiscais/contabilísticos.
8. Realizar testes de segurança, privacidade, recuperação e acessibilidade.

## Privacidade

Não inserir dados pessoais reais de alunos, encarregados ou funcionários neste repositório público. Para testes com dados reais, utilizar um ambiente privado, acesso restrito, autorização institucional e medidas adequadas de proteção de dados.

---
**CACP Beta 0.1 — protótipo não oficial, para discussão e demonstração.**
