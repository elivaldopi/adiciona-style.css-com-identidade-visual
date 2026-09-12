# Proj-front-UI
Repo projeto integrador - UESPI 

# Netinho.io — Guia do Litoral do Piauí

**Instituição:** Universidade Estadual do Piauí (UESPI)
**Disciplina:** UAPITSI19 - PROJETO INTEGRADOR II
**Docente:** [Inserir Nome do Professor]
**Equipe:**
- Vinicius Veras Silva
- [Inserir Nome do Integrante 2]
- [Inserir Nome do Integrante 3]

---

## 🎯 Objetivo Acadêmico

Este repositório contém o código-fonte do projeto **Netinho.io**, desenvolvido como requisito avaliativo para a disciplina de Projeto Integrador II. Trata-se de um aplicativo web interativo projetado em um único arquivo HTML (Single-Page Application), atuando como um guia digital do litoral piauiense. O sistema integra o consumo de dados em tempo real e um motor de intenções local para simular um atendimento inteligente através do mascote do projeto.

## 🌊 Funcionalidades Implementadas

- **Condições em Tempo Real:** Leitura e exibição da velocidade do vento (nós), direção, rajadas, temperatura, índice UV e condições do mar.
- **Previsão de Maré:** Modelo harmônico simplificado integrado para estimativas de maré (com suporte arquitetural para futuras conexões a APIs oficiais).
- **Chatbot Interativo (Caju):** Motor de intenções executado localmente que responde a perguntas contextuais sobre as praias locais (Barra Grande, Barrinha, Macapá, Luís Correia, etc.), condições para a prática de kitesurf, informações sobre o Delta do Parnaíba e dicas de gastronomia.
- **Interface e Usabilidade:** Design responsivo com efeitos visuais fluidos ("Liquid Glass"), garantindo uma navegação limpa e objetiva.
- **Arquitetura Zero Dependências (Single-File):** Todo o HTML, CSS e JavaScript estão contidos e encapsulados em um único arquivo, facilitando a portabilidade e a execução.

## 🚀 Instruções para Avaliação

O projeto foi estruturado para ser executado sem a necessidade de processos complexos de compilação ou instalação de dependências locais. 

Para avaliar a aplicação:
1. Faça o clone deste repositório ou o download direto dos arquivos.
2. Abra o arquivo `guia do litoral piauiense.html` diretamente em qualquer navegador web moderno.
3. Utilize a interface principal para visualizar as chamadas de dados ou interaja com o campo de texto na parte inferior para testar as respostas do sistema de chat.

## ⚙️ Arquitetura e Consumo de APIs

O código-fonte possui um objeto `CONFIG` centralizado na tag `<script>` que gerencia a comunicação com os serviços externos:

- **Clima e Vento:** Integração nativa com a [Open-Meteo API](https://open-meteo.com/), consumindo dados públicos meteorológicos.
- **Mar e Ondas:** Integração com a Open-Meteo Marine API.
- **Chat e Processamento:** Lógica executada primordialmente via processamento no cliente (front-end).

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3** (Utilização de variáveis, animações nativas e propriedades de *backdrop-filter*)
- **Vanilla JavaScript** (ES6+, manipulação de DOM e Fetch API)
- **APIs de Terceiros:** Open-Meteo (Weather & Marine)
