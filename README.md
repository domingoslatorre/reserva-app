# Reserva App

Aplicação de exemplo para aulas sobre desenvolvimento web backend e criação de multipage applications utilizand Python e Flask.

## Usuários vs. Funcionalidades
- Administrador
  - Login
  - Reservar Sala
  - Ver Reservas
  - Cancelar Reserva
  - Gerenciar Salas
  - Logout
- Professor
  - Cadastrar
  - Login
  - Reservar Sala
  - Ver Reservas
  - Cancelar Reserva
  - Logout

## Models
- Usuário
  - codigo
  - nome
  - email
  - senha
  - ativo
  - admin
- Sala
  - codigo
  - capacidade
  - ativa
  - tipo
  - descricao
- Reserva
  - codigo
  - usuario
  - sala
  - data e hora início
  - data e hora fim
  - ativa
  