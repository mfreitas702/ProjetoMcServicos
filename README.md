# 🚀 Projeto Microsserviços com Docker e AWS

> Estrutura de microsserviços usando Docker, Linux e AWS EC2 ☁️

---

## 📚 Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio prático para consolidar conhecimentos em:

- Docker
- Linux (Ubuntu Server)
- AWS (EC2)
- Estruturação de Microsserviços

## 🛠️ Tecnologias Utilizadas

- Docker Engine
- Docker Compose
- Linux Ubuntu 22.04
- Amazon Web Services (EC2)
- Nginx
- MySQL (servidor de dados)

## 📦 Estrutura de Microsserviços

O projeto está dividido em três servidores distintos na AWS:

- **Servidor Web**: Contém o serviço Nginx para servir o front-end estático.
- **Servidor de Arquivos**: Responsável pelo armazenamento e disponibilização dos arquivos do site.
- **Servidor de Dados**: Hospeda um banco de dados MySQL para persistência das informações.

## 📈 Organização de Rede

- Criação de uma rede Docker chamada `microservices-network` para comunicação entre containers.
- Separação de responsabilidades entre serviços (princípio dos microsserviços).

## 📋 Como Rodar o Projeto

1. Clonar o repositório em cada servidor.
2. Executar `sudo docker-compose up -d` para subir os containers.
3. Garantir que as máquinas estejam liberadas na porta 80 (HTTP) e 3306 (MySQL) no Security Group da AWS.

## ✨ Aprendizados

Durante a implementação, foram enfrentados e solucionados problemas como conflitos de porta, containers antigos, redes Docker e dependências entre serviços. Todo o processo simula situações reais do mercado de tecnologia.

## 🔗 Inspirado por

Projeto de referência: [Toshiro Shibakita - Docker Microservices](https://github.com/shibakita/docker-microservices)

---

Feito com 💙 por Marina 🚀
