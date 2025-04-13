Este é um projeto didático desenvolvido para a disciplina de PRW1, com o objetivo de aplicar os conhecimentos adquiridos na criação de um sistema de agendamento de consultas médicas em formato SPA (Single Page Application), utilizando HTML, CSS, JavaScript e jQuery.

🔗 Webservice de Apoio
O sistema consome dados de um webservice RESTful disponível em:

📍 https://ifsp.ddns.net/webservices/clinicaMedica/

Esse webservice permite operações de CRUD para médicos, pacientes e consultas.

⚙️ Funcionalidades Implementadas

✅ Ver lista de pacientes cadastrados

✅ Ver lista de médicos cadastrados e suas especialidades

✅ Listar todas as consultas agendadas para um médico X

✅ Listar todas as consultas agendadas para um paciente Y

✅ Cadastrar uma nova consulta, associando médico e paciente existentes

✅ Editar informações de médicos ou pacientes (nome, data, especialidade)

✅ Remover uma consulta agendada

✅ Remover médicos ou pacientes do sistema

🛠 Tecnologias Utilizadas
HTML5 + CSS3

JavaScript ES6

jQuery

AJAX para comunicação com o webservice

SPA sem uso de frameworks adicionais

🚀 Como Executar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/clinica-medica-spa.git
cd clinica-medica-spa
Abra o arquivo index.html em um navegador moderno.

Navegue pela aplicação diretamente, sem necessidade de backend local, pois ela consome o webservice externo.

📁 Estrutura do Projeto
pgsql
Copiar
Editar
clinica-medica-spa/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── app.js
└── README.md

🧑‍⚕️ Sobre o Sistema
O sistema simula o funcionamento básico de uma clínica médica, permitindo o gerenciamento de cadastros e agendamentos. Foi desenvolvido com fins educacionais para praticar conceitos como:
Consumo de APIs REST
Manipulação dinâmica do DOM
Eventos com jQuery
SPA sem recarregar a página

📚 Licença
Este projeto é de uso didático e livre para fins educacionais.

