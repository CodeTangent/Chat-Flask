# 💬 Real-Time Chat com Flask e Socket.IO

## 🚀 Descrição

Aplicação web de chat em tempo real desenvolvida com Python e Flask, utilizando Socket.IO para comunicação bidirecional entre cliente e servidor.

---

## 🧠 Problema resolvido

Permitir troca de mensagens instantânea entre usuários sem necessidade de recarregar a página, utilizando comunicação baseada em eventos.

---

## 🛠 Tecnologias

* Python
* Flask
* Flask-SocketIO
* HTML / CSS / JavaScript
* WebSockets

---

## ⚙️ Funcionalidades

* Envio de mensagens em tempo real
* Comunicação bidirecional cliente-servidor
* Atualização dinâmica da interface
* Interface web simples e funcional

---

## 🔌 Como funciona

* O cliente envia mensagens via `socket.emit`
* O servidor recebe e retransmite (broadcast)
* Todos os clientes conectados recebem a mensagem instantaneamente
* A interface é atualizada sem refresh da página

---

## ▶️ Como executar

```bash id="4xts5z"
pip install flask flask-socketio
python app.py
```

Acesse:

```id="p6vh8y"
http://localhost:5000
```

---

## 📁 Estrutura do projeto

* `app.py` → servidor Flask + Socket.IO
* `templates/` → interface HTML
* `static/` → arquivos CSS

---

## 🎯 Objetivo do projeto

Explorar comunicação em tempo real em aplicações web utilizando WebSockets e Flask.

---

## 📈 Melhorias futuras

* Identificação de usuários
* Histórico de mensagens
* Persistência em banco de dados
* Salas de chat (rooms)
* Deploy em nuvem

---
