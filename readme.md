# Chat Básico – Projeto em Flask

## Visão Geral
Este projeto foi desenvolvido em Python utilizando Flask, com o objetivo de entender e praticar conceitos básicos de desenvolvimento web com esta biblioteca. A interface HTML/CSS é simples e não foi o foco do projeto, sendo apenas funcional para testes do backend.

O projeto demonstra como estruturar rotas, lidar com requisições HTTP e criar um chat básico com armazenamento temporário em memória.

## Funcionalidades Principais
- Chat em tempo real básico  
- Estrutura de rotas HTTP com Flask  
- Interface web funcional (HTML/CSS mínimo)  
- Armazenamento de mensagens em memória (sem banco de dados)  
- Demonstração de integração entre frontend e backend  

## Estrutura do Projeto
A estrutura de arquivos está organizada para facilitar entendimento e manutenção:

| Arquivo / Pasta      | Descrição                                                                                   |
|--------------------|--------------------------------------------------------------------------------------------|
| `app.py`           | Arquivo principal do projeto, contendo as rotas e a lógica do chat                           |
| `templates/`       | Pasta com os arquivos HTML do projeto                                                      |
| `static/`          | Pasta para arquivos estáticos como CSS e imagens                                           |

> Observação: O projeto é focado em aprendizado de Flask, sem persistência de dados em banco ou estilização avançada da interface.

## Conceitos Aplicados
- Python com Flask para desenvolvimento web  
- Criação de rotas e tratamento de requisições HTTP  
- Renderização de templates HTML com Jinja2  
- Armazenamento temporário de dados em memória  
- Integração simples entre frontend e backend  

## Como Funciona
1. Instale as dependências com `pip install flask`.  
2. Execute o arquivo `app.py` com Python 3.x.  
3. Acesse `http://localhost:5000` no navegador.  
4. Envie mensagens no chat para testar a interação básica.  

## Status do Projeto
- Chat básico funcional  
- Interface mínima implementada  
- Projeto em aprendizado, sem persistência de mensagens ou funcionalidades avançadas  

## Observações
Este projeto foi criado para fins educativos, permitindo experimentar Flask de forma prática e direta. Serve como base para futuros projetos web mais complexos.
