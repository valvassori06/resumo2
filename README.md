# resumo2
 Integração com Azure OpenAI e Semantic Kernel

O desafio propõe explorar o desenvolvimento de aplicações utilizando o Azure OpenAI, incluindo chamadas de API e a integração com o Semantic Kernel.

Azure OpenAI Service
O Azure OpenAI permite acessar modelos avançados de IA, como GPT, Codex e DALL·E, hospedados na infraestrutura da Microsoft. Ele oferece segurança, escalabilidade e integração com outros serviços do Azure.

Chamadas de API
Para interagir com os modelos, utilizamos a API REST do Azure OpenAI, que permite enviar solicitações e receber respostas em formato JSON. O processo envolve:

Autenticação: Feita via chave de API ou identidade gerenciada.
Configuração de endpoint: Definição do modelo e parâmetros como temperatura e máximo de tokens.
Envio de requisição: Uso de métodos HTTP como POST para processar prompts e receber respostas.
Semantic Kernel
O Semantic Kernel é uma ferramenta que facilita a integração entre modelos de IA e lógica de negócios. Ele oferece:

Orquestração de prompts: Permite criar fluxos estruturados de interações com a IA.
Memória contextual: Mantém o contexto das interações para gerar respostas mais coerentes.
Plugins: Integra a IA com funcionalidades personalizadas, como acesso a bancos de dados e APIs externas.
