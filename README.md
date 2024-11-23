# Lambda Redirect URL Shortener

Função Lambda para redirecionamento para URLs através de link encurtado criada durante o curso **Aplicação Serverless com Java e AWS** da Rocketseat, ministrado por **Fernanda Kipper**.

## 🚀 Funcionalidades
- Recebe URL com código encurtado no modelo url-aqui.com/{codigo-UUID-encurtador}
- Lê informações referentes ao código no bucket do S3
- Verifica se tempo de expiração ainda está válido
- Redireciona para URL

## 🛠 Tecnologias
- **Java**
- **AWS Lambda**
- **AWS API Gateway**
- **AWS S3**