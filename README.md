# Proj-front-UI - Neto.IA
Repo projeto integrador - UESPI 

Conversa com o Gemini
Crie um readmi para github desse projeto.

Prezado usuário, o seu arquivo Markdown (README) está pronto:

Ícone do app MD
README
 MD 
O documento sumariza o projeto "Netinho.io", descrevendo suas funcionalidades principais como o guia de condições climáticas (vento, clima e maré) e a interação com o mascote Caju. Além disso, a documentação detalha a sessão de configuração das APIs (através da constante CONFIG) e reforça os avisos críticos de segurança sobre o armazenamento de chaves no backend.  
HTML
+ 1

Com o objetivo de refinar este arquivo, o senhor gostaria de adicionar alguma seção complementar, como um guia para contribuição de desenvolvedores ou informações específicas de licenciamento do software?




O Gemini é uma IA e pode cometer erros.

Defining the Scope
# Netinho.io — Guia do Litoral do Piauí

Um aplicativo web interativo projetado em um único arquivo (Single-Page Application) para ser o seu guia definitivo do litoral piauiense. O Netinho.io oferece condições em tempo real de vento, clima e maré, além de um chatbot integrado com um mascote interativo (Caju).

## 🌊 Funcionalidades

- **Condições em Tempo Real:** Leitura de velocidade do vento (nós), direção, rajadas, temperatura, índice UV e condições do mar.
- **Previsão de Maré:** Modelo harmônico simplificado integrado para estimativas de maré, com suporte pronto para conexão a APIs oficiais.
- **Chatbot Interativo (Caju):** Motor de intenções local que responde perguntas sobre praias (Barra Grande, Barrinha, Macapá, Luís Correia, etc.), condições para kitesurf, Delta do Parnaíba, gastronomia e hospedagem.
- **Design "Liquid Glass":** Interface moderna, responsiva e com efeitos visuais fluidos.
- **Zero Dependências (Single-File):** Todo o HTML, CSS e JavaScript estão contidos em um único arquivo.

## 🚀 Como Executar

O projeto não requer processos complexos de compilação.
1. Clone este repositório.
2. Abra o arquivo `guia do litoral piauiense.html` diretamente em seu navegador.

## ⚙️ Configuração e APIs

O código-fonte possui um objeto `CONFIG` no início da tag `<script>` que permite plugar facilmente serviços de dados:

- **Clima e Vento:** Já configurado de forma nativa com a [Open-Meteo API](https://open-meteo.com/) (gratuita e sem necessidade de chave).
- **Mar e Ondas:** Utiliza a Open-Meteo Marine API.
- **Maré (Personalizável):** Atualmente utiliza uma estimativa por modelo. Você pode configurar a variável `urlMare` para apontar para o seu backend corporativo e consumir dados de tábuas oficiais (como DHN, WorldTides ou Stormglass).
- **Inteligência Artificial (Opcional):** O chat opera primariamente de forma local. Para habilitar respostas baseadas em LLM, defina `urlIA` com o endpoint do seu backend.

## 🔒 Segurança

- **Chaves de API:** NUNCA exponha chaves de API restritas diretamente neste arquivo HTML. Qualquer chamada que exija autenticação ou tarifação deve passar por um proxy/backend sob seu controle.
- **Ambiente de Produção:** Recomenda-se servir o arquivo utilizando cabeçalhos de *Content-Security-Policy* (CSP) adequados e transferir CSS/JS para arquivos externos.

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3** (Variáveis, animações e *backdrop-filter*)
- **Vanilla JavaScript** (ES6+, Fetch API)
- **APIs de Terceiros:** Open-Meteo
README.md
README.md
Exibindo README.md.Carregando README.md.
