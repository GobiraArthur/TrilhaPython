**CRIANDO UM AMBIENTE VIRTUAL PYTHON NO VS CODE**

------------



**Passo 1**: Crie um novo projeto no VS Code.<br>
Abra o VS Code e crie uma nova pasta para o seu projeto.

**Passo 2**: Abra o Terminal
No VS Code, vá para Terminal -> New Terminal.

**Passo 3**: Crie um ambiente virtual
Digite o seguinte comando no terminal para criar um ambiente virtual usando o módulo venv do Python. 

```python
python -m venv myenv
```
Isso criará uma pasta chamada myenv no diretório atual com todos os arquivos necessários para o ambiente virtual.

**Passo 4**: Ative o ambiente virtual
No terminal, digite o seguinte comando para ativar o ambiente virtual:

```python
myenv\Scripts\activate
```
Você verá (myenv) no início da linha de comando, indicando que o ambiente foi ativado com sucesso.

Instale pacotes necessários
Com o ambiente virtual ativado, você pode usar o pip para instalar pacotes. Por exemplo, para instalar o pacote numpy, digite:

```python
pip install numpypip 
```
Isso instalará o numpy apenas no ambiente virtual atual.

**Passo 5**: Desativar o ambiente virtual (opcional)
Quando terminar de trabalhar no seu projeto, você pode desativar o ambiente virtual digitando:

```python
deactivate

```
Isso restaurará o prompt do terminal para o ambiente global do seu sistema.
