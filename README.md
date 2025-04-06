# Sistema de Gestão de Oficina Mecânica 🚗🔧

## Descrição
Este projeto apresenta o esquema conceitual de um sistema de gerenciamento para uma oficina mecânica, focado no controle de ordens de serviço (OS), equipes de mecânicos, veículos e clientes.

Clientes podem registrar seus veículos na oficina e autorizar serviços de manutenção ou revisão. Cada veículo é designado a uma equipe que avalia o que precisa ser feito, gera a OS e executa os serviços com base em uma tabela de preços e peças.

## Entidades Principais
- Cliente
- Veículo
- Mecânico
- Equipe
- Ordem de Serviço
- Serviço
- Peça

## Justificativas de Design
- Utilizamos relacionamentos N:N onde há participação de múltiplos registros (ex: mecânicos em várias equipes, OS com vários serviços e peças).
- Criação de tabelas auxiliares para facilitar o rastreio e a composição de valores por serviço e peça.
