
# SmartCare Serviços

## 1. Sobre o projeto

O SmartCare Serviços é um protótipo de experiência digital desenvolvido para uma empresa fictícia de limpeza e manutenção.

O objetivo é facilitar o contato entre clientes e a empresa, permitindo que solicitações de serviços sejam registradas por meio de um formulário digital.

O sistema também possui um classificador automático desenvolvido em JavaScript, responsável por identificar a categoria do serviço e sugerir uma prioridade para o atendimento.

## 2. Problema identificado

Empresas de limpeza e manutenção frequentemente recebem solicitações por diferentes canais de comunicação, dificultando a organização e a identificação das necessidades dos clientes.

A proposta do SmartCare é centralizar a solicitação em uma interface simples e oferecer uma primeira classificação automática dos pedidos.

## 3. Funcionalidades do protótipo

- Página inicial de apresentação da empresa.
- Catálogo de serviços.
- Formulário de solicitação.
- Identificação automática da categoria do serviço.
- Sugestão automática de prioridade.
- Interface responsiva para computadores e celulares.

## 4. Serviços disponíveis

- Limpeza residencial.
- Limpeza comercial.
- Manutenção hidráulica.
- Pequenos reparos.

## 5. Tecnologias utilizadas

**HTML5:** estruturação do conteúdo da página.

**CSS3:** desenvolvimento do layout, cores, espaçamentos e responsividade.

**JavaScript:** implementação da lógica de classificação automática das solicitações.

**GitHub Pages:** hospedagem gratuita do protótipo.

## 6. Funcionamento do classificador

O classificador utiliza regras condicionais em JavaScript para analisar as informações preenchidas pelo usuário.

A categoria é definida conforme o serviço selecionado.

A prioridade considera a urgência informada pelo cliente e palavras-chave na descrição, como "inundação", "alagamento" e "vazamento intenso".

O resultado é apresentado automaticamente na tela.

A classificação é uma sugestão inicial e deve ser validada por um profissional responsável.

## 7. Como executar

1. Baixe ou clone o repositório.
2. Abra a pasta do projeto no Visual Studio Code.
3. Abra o arquivo `index.html` em um navegador.
4. Preencha o formulário e clique em "Analisar solicitação".

## 8. Limitações e melhorias futuras

O protótipo não possui banco de dados nem integração com sistemas externos para armazenamento das solicitações.

Como melhorias futuras, podem ser implementados:

- Integração com banco de dados.
- Envio automático de notificações por e-mail.
- Painel administrativo para gerenciamento dos pedidos.
- Integração com ferramentas de automação.
- Uso de inteligência artificial generativa para interpretação mais avançada das solicitações.

## 9. Considerações finais

O SmartCare demonstra como tecnologias web e lógica de programação podem ser utilizadas para desenvolver uma experiência digital funcional.

O projeto apresenta uma primeira etapa de automação do atendimento, reduzindo a necessidade de classificação manual inicial e organizando melhor as informações recebidas dos clientes.
