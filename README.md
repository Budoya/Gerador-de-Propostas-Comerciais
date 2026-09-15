# Gerador-de-Propostas-Comerciais
Desenvolvi melhorias e funcionalidades em uma aplicação desktop construída com Electron e Angular para automação de propostas comerciais, integrando dados de CRM e reduzindo o esforço manual da equipe de vendas através da centralização de informações, cálculos tributários e parametrizações comerciais.
- Visão Geral

O Gerador de Propostas Comerciais é uma aplicação desktop responsável por consolidar informações de negociações provenientes de um CRM e transformar esses dados em propostas de venda padronizadas.

A solução foi criada para reduzir atividades manuais da equipe comercial, garantindo maior agilidade, consistência documental e padronização dos processos de venda.

- Principais Funcionalidades
Consulta de oportunidades comerciais através de integração com CRM.
Recuperação automática de informações da negociação.
Configuração de descontos e condições comerciais.
Parametrização de impostos e taxas.
Definição de prazo de validade da proposta.
Configuração de câmbio para negociações internacionais.
Inclusão de observações comerciais específicas.
Geração automatizada de propostas comerciais.
Interface desktop para utilização pela equipe de vendas.

⚙️ Fluxo de utilização
O vendedor registra a negociação no CRM.
São cadastrados os dados do cliente e dos produtos, incluindo:
quantidade;
valor;
desconto;
condições comerciais aplicáveis.
Na aplicação desktop, o vendedor busca a negociação pelo seu identificador.
A aplicação recupera e organiza as informações disponíveis no CRM.
O usuário complementa os dados específicos da proposta:
ICMS ou informações tributárias aplicáveis;
prazo de validade;
detalhes e observações comerciais;
cotação da moeda referente ao período;
outras condições específicas da negociação.
A aplicação valida e consolida os dados da proposta.
O documento é preparado para visualização e impressão.
Como etapa final, o usuário pode imprimir a proposta ou salvá-la em PDF utilizando as configurações nativas de impressão do Windows.
📄 Emissão do documento

Após o preenchimento e a validação das informações, a proposta é apresentada em um formato preparado para impressão.

A aplicação utiliza o fluxo nativo de impressão do Windows, permitindo que o usuário:

selecione uma impressora disponível;
ajuste orientação, escala e tamanho do papel;
configure margens e preferências de impressão;
gere o documento com a opção Microsoft Print to PDF, quando disponível;
escolha o diretório e o nome do arquivo final.

A aplicação prepara o conteúdo da proposta para impressão, enquanto a criação do arquivo PDF é realizada pelo mecanismo de impressão disponível no sistema operacional.

🛠️ Tecnologias Utilizadas
Front-end
Angular
TypeScript
HTML5
CSS3
NGX Libraries
Desktop
Electron
Build & Tooling
Webpack
Babel
Node.js
