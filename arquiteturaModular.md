project/
│
├── app/
│   ├── __init__.py          # Configuração inicial do app
│   ├── routes.py            # Definição de rotas (endpoints)
│   ├── models.py            # Definição de modelos de dados
│   ├── services/
│   │   ├── __init__.py      # Inicialização dos serviços
│   │   ├── user_service.py  # Lógica de negócios para usuários
│   │   ├── auth_service.py  # Lógica de autenticação
│   └── utils/
│       ├── __init__.py      # Inicialização de utilidades
│       ├── validators.py    # Funções para validação
│       └── helpers.py       # Funções auxiliares
│
├── tests/
│   ├── test_routes.py       # Testes para as rotas
│   ├── test_services.py     # Testes para os serviços
│
├── config.py                # Configuração do projeto (DB, etc.)
├── main.py                  # Ponto de entrada do aplicativo
└── requirements.txt         # Dependências do projeto
