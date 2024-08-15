# Deploy na AWS com Terraform

### Para rodar esse projeto

1. Faça um git clone: `git clone https://github.com/lorenzouriel/deploy-to-aws-terraform.git`

2. Construa a imagem Docker:
```bash
docker build -t app-streamlit .
```

3. Rode o contêiner:
```bash
docker run -p 8501:8501 app-streamlit
```

4. Acesse a aplicação em `http://localhost:8501`.

5. Verifique o arquivo `main.tf` e inicialize as configurações.
```bash
terraform init
terraform apply
```

6. Acesse a aplicação usando o IP público da instância EC2.

### Arquitetura
- ![arquitetura](/docs/architecture.png)

---
---
---
# Deploy on AWS with Terraform

### To run this project

1. Make a git clone: ​​`git clone https://github.com/lorenzouriel/deploy-to-aws-terraform.git`

2. Build a Docker image:
```bash
docker build -t app-streamlit.
```

3. Surrounded container:
```bash
docker run -p 8501:8501 app-streamlit
```

4. Access the application at `http://localhost:8501`.

5. Check the `main.tf` file and boot into settings.
```bash
terraform initialization
apply terraform
```

6. Access the application using the public IP of the EC2 instance.

### Architecture
- ![architecture](/docs/architecture.png)