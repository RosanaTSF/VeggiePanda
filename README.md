# VeggiePanda 🐼🥦
Bem-vindo ao **VeggiePanda**, um Delivery Vegano de Comidas Kawaii que explora as funcionalidades do AWS Step Functions de forma divertida e educativa! Este README é o nosso "menu" de conceitos e técnicas que você vai degustar, juntamente com detalhes sobre a AWS.

## Sobre a AWS
A Amazon Web Services (AWS) é uma plataforma de serviços em nuvem oferecida pela Amazon, que fornece infraestrutura e serviços para desenvolvimento de aplicações escaláveis e seguras. Os serviços da AWS, como o **AWS Step Functions**, permitem automatizar e gerenciar fluxos de trabalho complexos de forma simplificada.

## Menu Conceitual

### Entradas 🍤
**1. Pliés de Inicialização - Conceitos de AWS Step Functions**
- Introdução sobre o que são AWS Step Functions e como elas ajudam a orquestrar serviços e processos na nuvem.
- Benefícios de usar Step Functions, como automação e visibilidade de fluxos.

**2. Tacos de Transição - Estados e Transições**
- Explicação sobre os tipos de estados: `Task`, `Choice`, `Parallel`, `Wait`, etc.
- Como configurar transições e a importância do fluxo de trabalho definido.

### Pratos Principais 🍛
**3. Curry Lambda - Integração com AWS Lambda**
- Como conectar funções Lambda em uma Step Function para executar operações serverless.
- Passagem de dados entre estados e funções Lambda para manipulação de dados e processos.

**4. Risoto Wait - Estados de Espera**
- Uso do estado `Wait` para pausar o fluxo por um tempo determinado.
- Exemplos práticos para simular tempos de espera em processos, como a preparação de um prato.

**5. Stir-fry Choice - Estados Condicionais**
- Implementação de lógica condicional com o estado `Choice`.
- Casos de uso em que diferentes rotas de entrega ou opções de preparo são escolhidas com base em condições específicas.

### Acompanhamentos 🍙
**6. Salada Parallel - Execuções em Paralelo**
- Como executar múltiplos processos simultaneamente com o estado `Parallel`.
- Exemplos para gerenciar etapas que podem ocorrer ao mesmo tempo, como a preparação e a embalagem de um pedido.

**7. Wraps de Recurso - Permissões e Segurança na AWS**
- Práticas de segurança para conceder permissões mínimas necessárias às funções através de políticas IAM.
- Configuração de funções do IAM para Step Functions e Lambda para garantir a segurança dos processos.

### Sobremesas 🍨
**8. Bolo Error Handling - Tratamento de Erros e Retentativas**
- Como configurar retentativas automáticas e estratégias de fallback em AWS Step Functions.
- Métodos de lidar com erros para manter a robustez dos fluxos de trabalho.

**9. Smoothie de Monitoramento - Logs e Rastreamento na AWS**
- Uso do **Amazon CloudWatch** para monitorar e rastrear execuções de Step Functions.
- Como analisar logs detalhados para identificar gargalos e otimizar processos.

**10. Mousse Finalização - Boas Práticas e Otimização**
- Boas práticas de design para criar fluxos de trabalho eficientes e econômicos.
- Estratégias de otimização para reduzir custos e melhorar a performance geral dos processos.

## Como Pedir 🍱
Para usar as funcionalidades do **VeggiePanda** e explorar os conceitos:
1. Clone este repositório.
2. Configure suas credenciais da AWS para acesso aos serviços.
3. Execute os scripts que criam as Step Functions e as Lambdas para simular o fluxo do delivery.

## Imagem do Logo
![VeggiePanda Logo](../assets/veggie.PNG)

Aproveite a experiência do **VeggiePanda** e veja como os conceitos de AWS Step Functions e outros serviços da AWS podem transformar a forma de gerenciar processos de um delivery (e muito mais)!

## Dicionário de Termos
- **AWS Step Functions**: Serviço da AWS que orquestra múltiplos serviços e automações em um fluxo de trabalho visual.
- **AWS Lambda**: Serviço serverless que permite executar código sem provisionar ou gerenciar servidores.
- **Task State (Estado de Tarefa)**: Um estado de Step Function que realiza uma tarefa, como chamar uma função Lambda.
- **Choice State (Estado Condicional)**: Permite a execução de caminhos diferentes com base em condições definidas.
- **Parallel State (Estado Paralelo)**: Permite que vários ramos sejam executados ao mesmo tempo.
- **Wait State (Estado de Espera)**: Pausa o fluxo de trabalho por um tempo específico.
- **IAM (Identity and Access Management)**: Serviço da AWS que controla permissões e acesso aos recursos.
- **CloudWatch**: Serviço de monitoramento e observação que ajuda a gerenciar logs e métricas de aplicações.

Se divirta e explore como as **Step Functions** e outros conceitos da AWS podem ser aplicados ao mundo do delivery com um toque de diversão e aprendizado!
