---

# 🏥 Clínica Médica SPA

Este é um projeto didático desenvolvido para a disciplina de PRW1 em 2023, com o objetivo de aplicar os conhecimentos adquiridos na criação de um sistema de **agendamento de consultas médicas** em formato **SPA (Single Page Application)**, utilizando **HTML**, **CSS**, **JavaScript** e **jQuery**.

## 🔗 Webservice de Apoio

O sistema consome dados de um **webservice RESTful** disponível em:

📍 [https://ifsp.ddns.net/webservices/clinicaMedica/](https://ifsp.ddns.net/webservices/clinicaMedica/)

Esse webservice permite operações de CRUD para médicos, pacientes e consultas.

---

## ⚙️ Funcionalidades Implementadas

✅ Ver lista de **pacientes** cadastrados  
✅ Ver lista de **médicos** cadastrados e suas especialidades  
✅ Listar todas as **consultas agendadas para um médico X**  
✅ Listar todas as **consultas agendadas para um paciente Y**  
✅ **Cadastrar uma nova consulta**, associando médico e paciente existentes  
✅ **Editar** informações de médicos ou pacientes (nome, data, especialidade)  
✅ **Remover** uma consulta agendada  
✅ **Remover** médicos ou pacientes do sistema

---

## 🛠 Tecnologias Utilizadas

- HTML5 + CSS3  
- JavaScript ES6  
- [jQuery](https://jquery.com/)  
- AJAX para comunicação com o webservice  
- SPA sem uso de frameworks adicionais

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/clinica-medica-spa.git
   cd clinica-medica-spa
   ```

2. Abra o arquivo `index.html` em um navegador moderno.

3. Navegue pela aplicação diretamente, sem necessidade de backend local, pois ela consome o webservice externo.

---

## 🧑‍⚕️ Sobre o Sistema

O sistema simula o funcionamento básico de uma clínica médica, permitindo o gerenciamento de cadastros e agendamentos. Foi desenvolvido com fins educacionais para praticar conceitos como:

- Consumo de APIs REST
- Manipulação dinâmica do DOM
- Eventos com jQuery
- SPA sem recarregar a página

---
Claro! Aqui está uma seção que você pode adicionar ao final do seu `README.md` com instruções de uso via Docker:

---

## 🐳 Executando com Docker

Se preferir executar o projeto em um contêiner Docker, siga os passos abaixo:

### 📁 Pré-requisito

* Ter o **[Docker](https://www.docker.com/products/docker-desktop/)** instalado no seu sistema.

### ⚙️ Passos para rodar a aplicação

1. Certifique-se de estar dentro da pasta `site` (onde está o arquivo `index.html`).

2. No terminal, navegue até a pasta do projeto (onde está o Dockerfile) e execute:

   ```
   docker build -t clinica-medica-site .
   docker run -p 8080:80 clinica-medica-site
   ```

3. Acesse a aplicação no navegador em:

   ```
   http://localhost:8080
   ```

> Isso irá rodar a SPA dentro de um servidor Nginx usando Docker, tornando o acesso e deploy local mais prático e padronizado.

---

## 📚 Licença

Este projeto é de uso didático e livre para fins educacionais. Agradecimentos à zFefeu, Kayky e Maciel por fazerem parte do grupo que desenvolveu esse site.

---
