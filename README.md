# Machine Learning para Engenharia: Casos Práticos

Este repositório é parte de uma série didática que explora conceitos fundamentais de **Aprendizado de Máquina** (Machine Learning) por meio de casos práticos aplicados em diferentes disciplinas da engenharia, como **elétrica**, **mecânica** e **de petróleo**. Nosso objetivo é oferecer uma abordagem clara e acessível, conectando teoria e prática com exemplos reais que auxiliam na solução de problemas complexos.

## 🌍 **Objetivo Geral**

Demonstrar como **Machine Learning** pode ser aplicado em problemas reais da engenharia, promovendo eficiência, segurança e redução de custos, utilizando dados e técnicas modernas de aprendizado de máquina.

---

## 📂 **Como Baixar o Repositório**

1. Acesse a página do repositório no GitHub.
2. Clique no botão **Code** e escolha uma das opções:
   - **Download ZIP**: Para baixar diretamente o repositório compactado.
   - **Clone via HTTPS/SSH**: Copie o link e use o seguinte comando no terminal:
     ```bash
     git clone https://github.com/IamIK01/ml_in_engineering_series.git
     ```
3. Os notebooks estarão disponíveis para acesso via [Kaggle](https://www.kaggle.com/) e [Google Colab](https://colab.research.google.com/). Essas ferramentas configuram criam automaticamente um ambiente de trabalho em cloud configurado com todas as dependências necessárias para executar código e Python. São excelentes para ML, Análise de Dados e prototipagem em geral.
---

## 🤖 **Configuração do Ambiente Python**

Para executar os códigos deste projeto, é necessário ter o Python instalado no seu sistema. Siga um dos métodos abaixo:

### **Instalando o Python**

#### **Windows**

1. Baixe o instalador no site oficial do Python: [python.org](https://www.python.org/).
2. Durante a instalação, selecione a opção **Add Python to PATH**.
3. Verifique a instalação:
   ```bash
   python --version
   ```

#### **Linux (Debian/Ubuntu)**

1. Atualize os pacotes:
   ```bash
   sudo apt update && sudo apt upgrade
   ```
2. Instale o Python:
   ```bash
   sudo apt install python3 python3-pip
   ```
3. Verifique a instalação:
   ```bash
   python3 --version
   ```

#### **macOS**

1. Instale o Homebrew, caso ainda não tenha:
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
2. Instale o Python:
   ```bash
   brew install python
   ```
3. Verifique a instalação:
   ```bash
   python3 --version
   ```

---

### **Configurando com Conda**

Caso prefira usar o gerenciador de pacotes Conda, siga os passos abaixo:

1. Certifique-se de que o Conda esteja instalado no seu sistema. Caso contrário, baixe e instale o [Miniconda](https://docs.conda.io/en/latest/miniconda.html) ou o [Anaconda](https://www.anaconda.com/).

2. Navegue até o diretório do repositório clonado:
   ```bash
   cd <nome-do-diretório>
   ```

3. Crie um novo ambiente Conda:
   ```bash
   conda create --name ml_engineering python=3.9
   ```

4. Ative o ambiente:
   ```bash
   conda activate ml_engineering
   ```

5. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

6. Confirme que as dependências foram instaladas corretamente:
   ```bash
   pip list
   ```

---

### **Criando o Ambiente Virtual (sem Conda)**

Recomenda-se criar um ambiente virtual para gerenciar as dependências do projeto. Siga os passos:

1. Navegue até o diretório do repositório clonado:
   ```bash
   cd <nome-do-diretório>
   ```

2. Crie o ambiente virtual:
   ```bash
   python3 -m venv venv
   ```

3. Ative o ambiente virtual:
   - **Windows**:
     ```bash
     .\venv\Scripts\activate
     ```
   - **Linux/macOS**:
     ```bash
     source venv/bin/activate
     ```

4. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

5. Confirme que as dependências foram instaladas corretamente:
   ```bash
   pip list
   ```

---

## 🔧 **Executando o Código**

1. Certifique-se de que o ambiente virtual ou Conda esteja ativado.

2. Execute os scripts Python diretamente no terminal:
   ```bash
   python <nome-do-script>.py
   ```

3. Para notebooks Jupyter, inicie o servidor:
   ```bash
   jupyter notebook
   ```

---

## 🎮 **Contribuições**

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para aprimorar este projeto.

---

