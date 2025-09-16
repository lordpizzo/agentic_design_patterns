# Agentic Design Patterns

Este projeto explora padrões de design para sistemas agênticos usando Python.

## 🚀 Configuração do Ambiente

### Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)

### Configuração do Ambiente Virtual

1. **Clone ou navegue até o diretório do projeto:**
   ```bash
   cd agentic_design_patterns
   ```

2. **Crie o ambiente virtual:**
   ```bash
   python3 -m venv venv
   ```

3. **Ative o ambiente virtual:**
   
   **No macOS/Linux:**
   ```bash
   source venv/bin/activate
   ```
   
   **No Windows:**
   ```bash
   venv\Scripts\activate
   ```

4. **Atualize o pip (recomendado):**
   ```bash
   pip install --upgrade pip
   ```

5. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

### Verificação da Instalação

Para verificar se tudo foi instalado corretamente:

```bash
python --version
pip list
```

### Desativação do Ambiente Virtual

Quando terminar de trabalhar no projeto:

```bash
deactivate
```

## 📁 Estrutura do Projeto

```
agentic_design_patterns/
├── venv/                 # Ambiente virtual Python
├── chapter-1/           # Capítulo 1 do projeto
├── requirements.txt     # Dependências do projeto
└── README.md           # Este arquivo
```

## 🔧 Comandos Úteis

### Adicionar novas dependências

1. Ative o ambiente virtual
2. Instale o pacote: `pip install nome_do_pacote`
3. Atualize o requirements.txt: `pip freeze > requirements.txt`

### Reinstalar dependências

Se você clonar este projeto em uma nova máquina:

```bash
python3 -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
pip install -r requirements.txt
```

## 📝 Notas Importantes

- **Sempre ative o ambiente virtual** antes de trabalhar no projeto
- **Não commite a pasta `venv/`** no controle de versão (já está no .gitignore)
- **Mantenha o `requirements.txt` atualizado** quando adicionar novas dependências
- **Use `python` em vez de `python3`** quando o ambiente virtual estiver ativo

## 🤝 Contribuição

1. Ative o ambiente virtual
2. Instale as dependências de desenvolvimento
3. Faça suas alterações
4. Execute os testes (quando disponíveis)
5. Atualize a documentação se necessário

---

**Dica:** Se você estiver usando VS Code, ele pode detectar automaticamente o ambiente virtual e sugerir usá-lo como interpretador Python para o projeto.