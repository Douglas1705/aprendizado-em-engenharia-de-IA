# 1. Instalação do Ambiente de Desenvolvimento

## Objetivo

Nesta etapa do curso de **LLM Engineering**, configurei o ambiente de desenvolvimento que será utilizado durante os exercícios e projetos da formação.

Ferramentas instaladas:

- [Cursor IDE](#11-cursor-ide)
- [UV](#12-uv)
- [Jupyter](#13-jupyter)
- [Referências](#referências)

---

## 1.1 Cursor IDE

> O Cursor é um editor de código baseado no VS Code que incorpora recursos de inteligência artificial diretamente ao fluxo de desenvolvimento. Ele é capaz de compreender o contexto do projeto para auxiliar na escrita, refatoração, revisão e depuração de código.


### Principais características

- Compatibilidade com o ecossistema do VS Code (temas, extensões e atalhos).
- Assistência por IA integrada ao editor.
- Geração e refatoração de código.
- Criação de testes automatizados.
- Chat contextual com acesso ao código do projeto.

### Instalação

Site oficial:

https://cursor.com/download

### Minha percepção

O principal diferencial do Cursor em relação ao VS Code é a integração nativa com inteligência artificial, reduzindo a dependência de extensões externas para tarefas de desenvolvimento assistido.

---

## 1.2 UV

> UV é um gerenciador de pacotes e projetos Python desenvolvido pela Astral e escrito em Rust. A ferramenta busca unificar funcionalidades tradicionalmente distribuídas entre soluções como pip, venv, pipx e Poetry.

### Principais recursos

- Instalação rápida de dependências.
- Criação e gerenciamento de ambientes virtuais.
- Gerenciamento de projetos Python via `pyproject.toml`.
- Controle de versões do Python.
- Execução de ferramentas e scripts isolados.

### Instalação

Documentação oficial:

https://docs.astral.sh/uv/getting-started/installation/

No Windows, execute o PowerShell como Administrador e utilize o comando:

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### Minha percepção

O UV se apresenta como uma alternativa moderna para gerenciamento de ambientes Python, simplificando tarefas que normalmente exigiriam várias ferramentas diferentes.

---

## 1.3 Jupyter

> Jupyter Notebook é um ambiente interativo amplamente utilizado em Ciência de Dados, Machine Learning e Inteligência Artificial. Ele permite combinar código, documentação, visualizações e resultados em um único arquivo.
> Para mais informações acesse: - [2. Notebook Jupyter](./2_Notebook_Jupyter.ipynb)

### Principais características

- Execução interativa de código.
- Organização de análises em células.
- Visualização de gráficos e resultados diretamente no notebook.
- Suporte a documentação utilizando Markdown.
- Integração com fluxos de trabalho de Machine Learning e IA.

### Extensão para Cursor

Instalação:

1. Abra o Cursor.
2. Acesse **View → Extensions**.
3. Pesquise por **Jupyter**.
4. Instale a extensão oficial.

### Arquivos Jupyter

A extensão padrão dos notebooks é:

```text
.ipynb
```

O GitHub possui suporte nativo para visualização desse formato diretamente no navegador.

### Minha percepção

O Jupyter é uma ferramenta importante para experimentação e prototipação, especialmente em projetos envolvendo análise de dados, treinamento de modelos e desenvolvimento de aplicações com IA.

---

## Aprendizados

Após esta etapa, compreendi:

- O papel do Cursor como IDE com recursos nativos de IA.
- Como o UV simplifica o gerenciamento de projetos Python.
- A importância do Jupyter Notebook para experimentação e documentação de projetos de IA.
- A estrutura básica necessária para acompanhar o restante do curso.

---

## Referências

- https://cursor.com
- https://docs.astral.sh/uv
- https://jupyter.org