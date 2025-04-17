# Desafio Técnico Flutter: Aplicativo de Quiz

## Visão Geral 📱

Desenvolva uma aplicação de quiz utilizando Flutter baseada no layout fornecido no Figma [aqui](https://www.figma.com/design/ULdLhDknWDYZMDz2EthqHA/Desafio-Mobile-Quiz?node-id=0-1&m=dev&t=QGZDoXtVkLLf4en3-1). 
O aplicativo deve permitir que os usuários respondam a perguntas de múltipla escolha e visualizem seus resultados ao final do quiz.

## Requisitos Funcionais 🛠️

1. **Tela do Quiz**
   - Exibir uma pergunta por vez com 4 opções de resposta (A, B, C e D)
   - Mostrar um indicador de progresso na parte superior (ex: 1/5)
   - Mostrar o título do quiz (ex: "Quiz #156")
   - Exibir um contador de pontos (valor "60" no design)
   - Implementar um botão "CONTINUAR" que é habilitado apenas após a seleção de uma alternativa
   - Quando uma opção é selecionada, destacá-la visualmente conforme o design do Figma

2. **Tela de Resultado**
   - Exibir o título "Resultado do Quiz #156" (ou o número do quiz atual)
   - Mostrar os pontos ganhos (ex: "120")
   - Exibir a quantidade de acertos (ex: "4")
   - Implementar um botão "TENTAR NOVAMENTE" para reiniciar o quiz
   - Incluir uma ilustração/ícone na parte superior da tela

## Requisitos Técnicos 💻

### Obrigatórios:

- **Fidelidade ao Design:**
  - Implementar a interface exatamente como mostrada no Figma
  - Utilizar as mesmas cores, fontes e espaçamentos
  - Implementar estados visuais para opções selecionadas/não selecionadas

- **Estrutura do Projeto:**
  - Organizar o código separando UI, lógica e dados
  - Seguir boas práticas de nomenclatura
  - Aplicar conceitos básicos de Clean Code

- **Dados:**
  - Criar um conjunto de pelo menos 5 perguntas com suas respectivas respostas
  - Implementar um modelo de dados para representar perguntas e respostas

- **Navegação:**
  - Implementar navegação entre a tela do quiz e a tela de resultados
  - Garantir que o fluxo de navegação esteja funcionando corretamente

- **Testes:**
  - Implementar testes unitários para as regras de negócio do quiz
  - Implementar testes de widget para componentes de perguntas e respostas
  - Implementar ao menos um teste de integração para o fluxo completo de um quiz

- **Controle de Versão:**
  - Utilizar Git com commits descritivos
  - Criar um README.md com instruções de como executar o projeto

### Diferenciais:

- **Gerenciamento de Estado:**
  - Implementar uma solução de gerenciamento de estado (Provider, Bloc, MobX ou GetX)
     - Justificar a escolha da solução no README
  - Separar a lógica de apresentação da lógica de negócio

- **Persistência:**
  - Salvar a maior pontuação do usuário usando SharedPreferences ou outro método de armazenamento local
  - Armazenar localmente o histórico de quizzes realizados e pontuações

- **Aprimoramentos:**
  - Implementar um temporizador funcional (contagem regressiva)
  - Calcular pontuação com base no tempo de resposta
  - Adicionar animações nas transições entre as perguntas e na seleção das respostas

- **Tela de Perfil/Histórico**
   - Exibir histórico de quizzes realizados 

- **API e Dados:**
  - Consumir dados da API pública [Open Trivia Database](https://opentdb.com/api_config.php) ou similar
  - Implementar tratamento adequado de erros e estados de carregamento   

## Entregáveis 📦

1. Pull Request da sua branch para a branch "desafio" no repositório [base](https://github.com/ciandt-edilsonr/desafio_flutter)
2. README.md contendo:
   - Descrição do projeto
   - Instruções para executar o aplicativo
   - Explicação da estrutura do código
   - Bibliotecas utilizadas (se houver)
   - Screenshots ou Vídeo do app em funcionamento

## Prazo ⏰

5 dias a partir do recebimento do desafio.

---

### Observações Importantes

- O desafio visa avaliar sua capacidade de transformar um design em código Flutter funcional
- Foque em implementar corretamente a UI e a lógica básica do quiz antes de adicionar os diferenciais
- A implementação exata das cores e estilos conforme o Figma é importante
- Não é necessário implementar backend ou API, trabalhe com dados locais

Boa sorte! 🚀