# DSML
Mercado Livre Data Science

# Basics (Project) - Preparação do Ambiente
1. Instalar o python3 via gerenciador de pacote do Sistema Operacional

    ```shell script
      # MacOS X
      $ brew install python3

      # Linux
      $ apt-get install python3

      # Windows 10 (GitBash)
      $ /c/Users/ilton/AppData/Local/Programs/Python/Python38/python.exe -m pip install --upgrade pip
    ```

1. Configuração do Virtual Env (VENV)

    1. Criação do VENV
        ```shell script
           # Vem instalado com o PIP, não precisa instalar o VirtualEnv
           $ virtualenv -p python3 venv
        ```

    1.  Ativando o VENV (faça isso toda vez que for executar o projeto)
        ```shell script
            # MacOS
            $ source venv/bin/activate

            # Windows (Gitbash)
            $  /c/Users/ilton/Google\ Drive/MercadoLivreDataScience/venv/Scripts/activate.bat
            # Windows (Prompt)
            > cd C:\Users\ilton\Google Drive\MercadoLivreDataScience
            > venv\Scripts\activate.bat
        ```

1. Instalando as dependências com as versões unificadas

    ```shell script
        # MAC
        $ pip install -r requirements_mac.txt
        # WINDOWS
        $ pip install -r requirements_win.txt
    ```

1. CASO ocorra erro no pandas profilling:

    ```shell script
        $ pip install https://github.com/pandas-profiling/pandas-profiling/archive/v2.9.0.zip
    ```


# Predictive
Principais Libs utilizadas:    
    *Algoritmos de Shallow Learning: SKLearn    
    *Algoritmos de Deep Learning: Keras + Tensorflow
    *PlotLib: Plotly
    *Report: [PandasProfilling](pip install https://github.com/pandas-profiling/pandas-profiling/archive/master.zip)

# Data Collector 
