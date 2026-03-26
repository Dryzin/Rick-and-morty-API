# Projeto Rick and Morty API

Este projeto foi desenvolvido com o foco em estudos, explorando ferramentas do ecossistema front-end moderno e práticas para a construção de aplicações em React e o consumo de dados de uma API externa. O projeto utiliza a famosa [Rick and Morty API](https://rickandmortyapi.com/) para listar e exibir informações sobre os personagens da série.

## 🚀 Tecnologias e Ferramentas Utilizadas

A aplicação faz uso das seguintes bibliotecas e ferramentas de desenvolvimento:

* **[React](https://reactjs.org/)**: Biblioteca JavaScript para construção de interfaces de usuário (UI). Responsável por viabilizar a componentização e gestão do estado na aplicação.
* **[Vite](https://vitejs.dev/)**: Ferramenta de build de frontend extremamente rápida, que atua como servidor de desenvolvimento otimizado e empacotador para produção.
* **[Axios](https://axios-http.com/)**: Cliente HTTP construído com base em *Promises*, facilitando muito o controle no fluxo de requisições GET/POST vindas de endpoints da internet bem como a interceptação de erros e dados.
* **[Styled-Components](https://styled-components.com/)**: Biblioteca de "CSS-in-JS". Permite escrever todo o CSS da aplicação e componentes através do JavaScript de forma encadeada, isolada e sem gerar conflitos de classe no escopo geral.
* **[ESLint](https://eslint.org/)**: Linter para manter a qualidade, coesão e a padronização na escrita de código ao longo do projeto.

## 🧠 Conceitos e Aprendizados Abordados

O desenvolvimento deste app cobriu de forma prática diversos conceitos essenciais para um desenvolvedor front-end:

* **Componentização UI**: Separação clara das responsabilidades da interface em pequenos componentes independentes e reutilizáveis ao longo da página, uma base da mentalidade de aplicações construídas em React.
* **Consumo de API Externa e Requisições HTTP**: 
  * Estruturação de métodos assíncronos que usam `async / await` ou manipulação de `Promises` (.then / .catch). 
  * Captura do retorno JSON de uma RESTful API real provida externamente e a injeção do conteúdo na view.
* **Gestão de Ciclo de Vida do React e Hooks**: 
  * Uso exaustivo de hooks triviais como o `useState` para armazenar momentaneamente os conjuntos de dados (personagens, status de carregamento, paginação).
  * O emprego do `useEffect` para gerar os "efeitos colaterais" assim que a tela monta ou quando certas dependências mudam de estado, disparando a requisição para a internet.
* **Renderização Dinâmica de Contexto/Listas**: Mapeamento do grande array de dados provido pela API (com uso do `.map()`) para iterar e construir componentes na árvore (DOM) de maneira contínua, extraindo em tempo real as propriedades, fotos e status.
* **Estilização com Escopo Global e Local**: 
  * Estruturação do React e Styles com Styled-Components, onde há suporte para injetar variáveis, encadear condicionais lógicas de propriedades de JS (`props`) mudando a aparência direto no estilho da tag.

## 🛠️ Como executar o projeto localmente

Para rodar este projeto em seu próprio ambiente, certifique-se de que tenha o [Node.js](https://nodejs.org/en) instalado em sua máquina e siga estes passos:

1. Acesse o diretório ou faça o clone do projeto (se aplicável).
2. Abra o terminal raiz da pasta e instale as dependências executando:
   ```bash
   npm install
   ```
3. Com tudo instalado, inicie o servidor virtual do Vite no qual foi compilado:
   ```bash
   npm run dev
   ```
4. Navegue pelo link indicado no terminal, por exemplo `http://localhost:5173/`, no seu browser.

---
_Anotação de estudos de consumo de APIs externas com requisições assíncronas._🚀
