# Lambda-com-Aliases
Nuvem AWS

# 📊 AWS Lambda com Aliases e API Gateway com Stages

## 📌 Descrição
Este laboratório demonstra uma prática essencial para gerenciar múltiplos ambientes (como desenvolvimento e produção)
de forma organizada e segura em aplicações serverless, utilizando as funcionalidades de versionamento e direcionamento do
Lambda e API Gateway.

---
## Cenário 

Fui contratado para desenvolver ou manter uma API serverless que serve como backend para uma aplicação. É crucial poder implantar e testar novas funcionalidades
ou correções em um ambiente isolado (desenvolvimento) antes de liberá-las para os usuários finais (produção). É necessário um mecanismo que permita ter endpoints
de API estáveis para cada ambiente (/dev/recurso e /prod/recurso, por exemplo), onde cada um invoque a versão apropriada do código da sua função Lambda, sem a
necessidade de criar APIs ou funções separadas para cada ambiente. Este laboratório implementa exatamente essa solução usando Aliases do Lambda e Stages do API
Gateway.

---
## 🚀 Tecnologias Utilizadas
- **Linguagem:** Python 3.9  
- **Bibliotecas:** Boto3  
- **AWS Lambda e Lambda Aliases**
- **API Gateway com Stages**
- **IAM**

---

## 🎯 Objetivos do Projeto
- ✅ Criar uma função AWS Lambda compatível com a integração Proxy do API Gateway. 
- ✅ Publicar diferentes versões da função Lambda para representar estados distintos do código.
- ✅ Criar Aliases no Lambda (ex: dev, prod) que funcionam como ponteiros para versões específicas da função.
- ✅ Criar uma API REST no API Gateway.
- ✅ Configurar a integração do tipo Proxy entre a API Gateway e a função Lambda.
- ✅ Criar Stages no API Gateway (ex: Desenvolvimento, Producao) para representar os diferentes ambientes de implantação da API.
- ✅ Integrar cada Stage da API Gateway com o Alias correspondente da função Lambda, garantindo que cada ambiente da API invoque a versão correta da função. 
- ✅ Testar os endpoints de cada Stage para verificar o correto direcionamento das chamadas.
- ✅ Compreender os benefícios do uso combinado de Aliases (Lambda) e Stages (API Gateway) para o gerenciamento do ciclo de vida e implantação controlada de aplicações serverless.

---

## 📂 Estrutura do Projeto
📁 AWS Lambda com Aliases e API Gateway com Stages

├── 📄 README.md <- Documentação do projeto

├── 📄 requirements.txt <- Dependências do Python

└── 📁 src/ <- Código-fonte organizado

---

## 📊 Resultados



## 1. Função Proxy Criada no Lambda
![1](https://github.com/user-attachments/assets/2f61c4ad-f915-4419-b7d7-89da0e496d2d)




## 2. Aliase do Lambda Criada
![2](https://github.com/user-attachments/assets/9111cf3e-4a40-4122-b765-e5555140f18a)




## 3. Aliase de Desenvolvimento e de Produção criadas
![3](https://github.com/user-attachments/assets/9139d4be-486c-4a5b-8d09-3771b0734c9e)




## 4. API Gateway para Desenvolvimento Criada
![4](https://github.com/user-attachments/assets/576da92e-8fe5-47a2-b8ef-cea2d10f4aa9)




## 5. Acessando o ambiente de Desenvolvimento pela API Gateway
![5](https://github.com/user-attachments/assets/9b726628-e669-428d-ae61-9dcd156d5657)
![6](https://github.com/user-attachments/assets/fdfab8a6-4251-4708-a605-b0bd9e24aeb7)


---

## 📎 Links Importantes
- 🔗 **Portfólio:** https://andrey-silva-data.github.io/MeuPortf-lio-AndreySilva/  
- 🔗 **LinkedIn:** https://www.linkedin.com/in/techprofessional-AndreySilva/ 
- 🔗 **GitHub:** https://github.com/Andrey-Silva-Data/Lambda-com-Aliases.git
---

## 📜 Licença
Todos os Direitos Reservados @Andrey Silva-2025.
