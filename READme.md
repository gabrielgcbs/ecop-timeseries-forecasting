# Antes de começarmos...

Precisamos configurar o ambiente.

- Assegure que o Python 3 está instalado (de preferência, $\geq$ 3.8);
- Abra o Terminal, seja no VSCode ou no Jupyter Lab;
- Crie o ambiente virtual:

``` bash
python -m venv .venv
```

- Ative o ambiente criado:

No Windows:

> PowerShell

``` bash
.venv\Scripts\Activate.ps1
```

> cmd

```bash
.venv\Scripts\activate.bat
```

No Linux:

``` bash
source .venv/bin/activate 
```

- Instale o ipykernel:

```bash
pip install ipykernel
```

> ⚠️ **Caso esteja usando o Jupyter Lab, execute o seguinte código**:

```bash
python -m ipykernel install --user --name=.venv
```

No notebook, selecione o ambiente virtual criado como o *Kernel*.
