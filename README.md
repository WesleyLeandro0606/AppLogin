AppLogin

Aplicativo Android desenvolvido em Java utilizando SQLite para realizar cadastro e login de usuários.

Funcionalidades

✅ Tela inicial do sistema

✅ Cadastro de usuários

✅ Login de usuários

✅ Validação de senha

✅ Confirmação de senha

✅ Armazenamento de dados com SQLite

✅ Navegação entre telas

✅ Mensagens de erro com Toast

✅ Validação de campos vazios

✅ Interface intuitiva

🛠 Tecnologias Utilizadas
Java
Android Studio
SQLite
XML
ConstraintLayout
📋 Componentes Utilizados
EditText
Button
TextView
Toast
Intent
SQLiteOpenHelper
📐 Funcionamento do Sistema

O aplicativo possui:

Tela inicial
Tela de login
Tela de cadastro
Banco de dados SQLite

O usuário pode:

Criar uma conta
Realizar login
Validar usuário e senha
💾 Banco de Dados SQLite

Tabela utilizada:

CREATE TABLE utilizador(
    username TEXT PRIMARY KEY,
    password TEXT
)
🔐 Validações Implementadas

O aplicativo verifica:

Campos vazios
Senhas diferentes
Usuário já existente
Login inválido

Mensagens são exibidas na tela para evitar erros no sistema.

⚠ Requisitos

Para executar o projeto é necessário ter instalado:

Android Studio
JDK (Java Development Kit)
Android SDK

Baixe o Android Studio:

Android Studio

▶ Como Executar
1. Clonar o projeto
git clone https://github.com/WesleyLeandro0606/AppLogin.git
2. Abrir no Android Studio
Clique em Open
Selecione a pasta do projeto
3. Executar o aplicativo
Conecte um celular Android ou utilize um emulador
Clique em ▶ Run
📱 Fluxo do Aplicativo
Usuário abre o aplicativo
Escolhe:
Entrar
Registrar
No cadastro:
informa usuário
cria senha
confirma senha
Os dados são salvos no SQLite
Usuário retorna para tela inicial
Pode realizar login no sistema
🚀 Melhorias Futuras
Criptografia de senha
Recuperação de senha
Tela principal após login
Design moderno
Lista de usuários cadastrados
👨‍💻 Autor

Projeto desenvolvido por Wesley Leandro Pinheiro Sebastiana.
