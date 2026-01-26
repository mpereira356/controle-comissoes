# Sistema de Controle de Comissões Profissional

Este é um sistema completo desenvolvido em Flask para gestão de comissões, baseado no layout original fornecido, mas com melhorias significativas em design, usabilidade e persistência de dados.

## Funcionalidades

- **Dashboard Moderno**: Visualização rápida de totais (Geral, Pagas, Pendentes e Atrasadas).
- **Banco de Dados**: Persistência real dos dados utilizando SQLite e SQLAlchemy.
- **Gestão Completa (CRUD)**: Adicionar, visualizar detalhes, marcar como pago e excluir registros.
- **Filtros Avançados**: Filtragem por vendedor, status e busca por nome de cliente.
- **Layout Responsivo**: Design profissional utilizando Bootstrap 5 e CSS personalizado.

## Como Executar

1. Certifique-se de ter o Python instalado.
2. Instale as dependências necessárias:
   ```bash
   pip install flask flask-sqlalchemy openpyxl
   ```
3. Execute a aplicação:
   ```bash
   python app.py
   ```
4. Acesse no seu navegador: `http://127.0.0.1:5000`

## Estrutura do Projeto

- `app.py`: Servidor Flask, modelos do banco de dados e rotas.
- `templates/`: Arquivos HTML (Jinja2).
- `static/`: Arquivos CSS e JavaScript.
- `instance/`: Localização do banco de dados SQLite.
# controle-comissoes
