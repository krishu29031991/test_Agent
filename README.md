etl_validator/
├── src/
│   ├── __init__.py
│   ├── parser/
│   │   ├── __init__.py
│   │   ├── excel_reader.py
│   │   ├── rule_parser.py
│   │   ├── join_parser.py
│   │   └── lookup_parser.py
│   ├── generator/
│   │   ├── __init__.py
│   │   ├── sql_builder.py
│   │   └── query_generator.py
│   ├── validator/
│   │   ├── __init__.py
│   │   ├── gcp_connector.py
│   │   ├── comparator.py
│   │   └── reporter.py
│   └── config.py
├── tests/
│   ├── test_parser.py
│   └── test_validator.py
├── requirements.txt
├── Dockerfile
├── main.py
└── .env
