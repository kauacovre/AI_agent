# Como utilizar o agente

** Passo a passo --- **
- Instale as dependências (Docker + vscode)
- Faça um clone desse repositório
- Rode o comando "docker-compose up -d" no terminal do seu vscode (Instala o "n8n + waha" através do docker)
- Abra o aplicativo do docker (interface gráfica)
- Na coluna "Port(s)", você pode acessar os links de "localhosts"
- **IMPORTANTE**: Ao acessar o "localhost: n8n", crie uma conta com um e-mail de acesso, pois irá gerar uma chave de ativação e enviar ao mesmo
- Dentro do n8n vá em -> settings -> usage and plan -> enter activation key (Cole a chave de ativação recebida)
- Logo em seguida acesse no menu lateral "Community nodes" e digite "n8n-nodes-waha" e instale a extensão do waha
- Acesse a API do waha atráves do "Aplicativo Docker"
- Ao entrar no link "localhost: waha" vá em > "dashboards"
- Dentro de "Sessions", você tem disponivel com o plano gratuido do waha apenas uma funcionalidade o "default"
- Do lado direito de "default" clique em "play/start" e espera carregar o "qr_code"
- Acesse no menu de "default" a opção "login", e pode estar utilizando o whatsapp desejado para colocar o agente de IA.
