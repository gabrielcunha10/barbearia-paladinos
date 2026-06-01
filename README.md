# 💈 Barbearia Paladinos

Sistema web desenvolvido em PHP para auxiliar na organização dos agendamentos e atendimentos da Barbearia Paladinos.

O projeto tem como objetivo facilitar a rotina da barbearia, permitindo o cadastro de clientes, barbeiros, serviços e agendamentos. A proposta também busca melhorar a experiência dos clientes ao marcar horários de forma mais prática.

## 📌 Contexto do projeto

Este sistema foi utilizado como parte de uma ação extensionista realizada na Barbearia Paladinos. A partir da entrevista com o barbeiro Thiago, foi identificada a necessidade de melhorar a organização dos horários, reduzir conflitos de agendamento e facilitar o atendimento aos clientes.

Durante o diagnóstico, foi observado que os agendamentos eram feitos principalmente pelo WhatsApp e por ligações, o que podia causar demora nas respostas e dificuldades no controle da agenda.

## 🚀 Funcionalidades

* Cadastro e login de clientes
* Cadastro de barbeiros
* Cadastro de serviços
* Agendamento de horários
* Controle de horários disponíveis e reservados
* Painel administrativo
* Gerenciamento de clientes
* Gerenciamento de barbeiros
* Gerenciamento de serviços
* Gerenciamento de agendamentos
* Página de fale conosco
* Banco de dados MySQL
* Interface responsiva
* Mensagem de confirmação após o agendamento

## 🗓️ Agendamento

O sistema permite que o cliente escolha uma data e um horário disponível para o atendimento. Os horários já ocupados ficam bloqueados, evitando que dois clientes marquem o mesmo horário.

Após realizar o agendamento, o cliente recebe a mensagem:

**Agendamento realizado com sucesso. Aguarde a confirmação da barbearia.**

## 🕒 Horário de funcionamento

* Terça a sexta-feira: 09:00 às 18:00
* Sábado: 09:00 às 14:00
* Domingo e segunda-feira: fechado

## ✂️ Serviços

* Barba Completa - R$ 25,00
* Corte + Barba - R$ 50,00
* Corte + Sobrancelha - R$ 45,00
* Corte Masculino - R$ 35,00
* Relaxamento Capilar - R$ 30,00

Alguns serviços podem ter durações diferentes. Para manter a organização da agenda, o sistema considera blocos de horário, evitando conflitos entre atendimentos.

## 📱 Instagram

Instagram da Barbearia Paladinos:

https://www.instagram.com/barbeariapaladinosjpa?igshid=YmMyMTA2M2Y%3D

## 🧰 Tecnologias utilizadas

* PHP 8 ou superior
* MySQL
* HTML5
* CSS3
* JavaScript
* Bootstrap
* Apache, via XAMPP ou WAMP

## 🖥️ Requisitos

Antes de executar o projeto, é necessário ter instalado:

* XAMPP ou WAMP
* PHP 8 ou superior
* MySQL
* Navegador atualizado

## ⚙️ Como executar o projeto

1. Clone o repositório:

```bash
git clone LINK_DO_REPOSITORIO
```

2. Copie a pasta do projeto para o diretório `htdocs` do XAMPP.

3. Inicie o Apache e o MySQL pelo painel do XAMPP.

4. Acesse o phpMyAdmin e importe o arquivo `.sql` do banco de dados.

5. Verifique os dados de conexão com o banco nos arquivos:

```txt
conectaPDO.php
conectaMYSQL.php
```

6. Acesse o projeto no navegador:

```txt
http://localhost/NOME_DA_PASTA_DO_PROJETO
```

## 💾 Banco de dados

A tabela principal de agendamentos utiliza campos como:

* id
* nome_cliente
* email_cliente
* telefone_cliente
* barbeiro
* servico
* horario

O campo `horario` é responsável por armazenar a data e a hora do agendamento.

## 👥 Integrantes da equipe

* Nome do integrante 1
* Nome do integrante 2
* Nome do integrante 3

## 🌱 Relação com a extensão

O projeto foi desenvolvido e apresentado como uma proposta de solução para a Barbearia Paladinos. A ação buscou aproximar o conhecimento acadêmico de uma necessidade real da comunidade, ajudando na organização dos atendimentos e na melhoria da rotina de trabalho.

O projeto se relaciona ao ODS 8, Trabalho decente e crescimento econômico, pois utiliza a tecnologia para melhorar a organização do trabalho, tornar o atendimento mais eficiente e contribuir para o funcionamento da barbearia.
