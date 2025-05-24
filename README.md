Plataforma de Educação Digital Segura

Projeto desenvolvido no 1º semestre de Análise e Desenvolvimento de Sistemas (UNIP).

Este sistema simula uma plataforma de ensino interativo focada na inclusão digital. O sistema foi desenvolvido em Python, com a interface web utilizando o framework Flask.

---

Funcionalidades

-  Cadastro e login de usuários com senha criptografada (hash SHA-256)
-  Registro dos cursos acessados pelos usuários
-  Visualização de estatísticas de uso (média, mediana e moda dos acessos)
-  Armazenamento de dados em arquivos JSON
-  Interface web simples com Flask e templates HTML
-  Códigos organizados por módulos (autenticação, conteúdo, estatísticas)

---

Tecnologias utilizadas

- Python 3.8+
- Flask
- HTML5 + CSS3
- JSON (para armazenamento local)

---

 Como executar

Rodar versão no terminal:

```bash
python main.py
```

Rodar versão web com Flask:

1. Instale o Flask (se ainda não tiver):
```bash
pip install flask
```

2. Execute o servidor Flask:
```bash
python app.py
```

3. Acesse no navegador:
```
http://localhost:5000
```

---

Estrutura do projeto

```
/portal-educacional
├── app.py               # Servidor Flask
├── main.py              # Versão terminal
├── utils/               # Lógica da aplicação
│   ├── auth.py
│   ├── content.py
│   ├── stats.py
│   └── storage.py
├── templates/           # HTML (para Flask)
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── cursos.html
├── static/              # CSS e arquivos estáticos
│   └── style.css
└── README.md
```

Licença

Este projeto é acadêmico e não possui licença aberta para uso comercial.

---

Feito com 💙 por Luan Oliveira
