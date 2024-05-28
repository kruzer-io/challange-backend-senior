# **Kruzer - Desafio Backend Sênior**

O desafio consiste na criação de três micro-serviços fundamentais para a gestão eficiente de um sistema de comércio eletrônico: catálogo de produtos (PIM), atendimento (CHECKOUT) e gestão de pedidos (OMS). Cada micro-serviço desempenha um papel específico e crucial na operação do sistema, atendendo aos requisitos de negócio e técnicos detalhados a seguir:

### **Requisitos de Negócio:**

- **Gestão de Catálogo (PIM)**: Este micro-serviço deve permitir a criação de produtos com informações essenciais, tais como código, nome e preço.
- **Gestão de Atendimento (CHECKOUT)**: Responsável por gerenciar atendimentos, incluindo produtos e informações dos compradores.
- **Gestão de Pedidos (OMS)**: Este micro-serviço deve receber um atendimento, processá-lo e transformá-lo em um pedido finalizado.

### **Requisitos Técnicos:**

- Cada micro-serviço deve ser independente, possuindo seu próprio servidor de API e banco de dados.
- Um serviço não pode conhecer nem se comunicar diretamente com outro serviço.
- Os serviços devem se comunicar através do Kafka, que atuará como message broker.
- Utilize Koa e DDD (Domain-Driven Design) com modelagem de entidades voltadas para o domínio de cada módulo.
- Os servidores devem ser construídos utilizando Docker e docker-compose para facilitar a implantação e o gerenciamento de contêineres.

### **Diferenciais:**

- Crie um instalador da aplicação utilizando uma imagem publicada no Docker Hub, permitindo que a plataforma seja instalada na máquina do usuário com um único comando Docker.
- Utilize o MongoDB - Change Streams para auxiliar na publicação de mensagens no Kafka, proporcionando uma solução mais robusta e eficiente para a troca de mensagens entre os micro-serviços.

---

Este desafio técnico oferece uma oportunidade para demonstrar habilidades avançadas em desenvolvimento de micro-serviços, design de arquitetura, integração de sistemas e implementação de tecnologias emergentes, bem como analisa a capacidade do candidato de encapsular todas essas tecnologias em um projeto funcional.
