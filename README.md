
# Popular Coins

## Contexto

O projeto é uma aplição Fullstack com Backend criado com Python utilizando Flask e Frontend com React e Typescript.
A Interface consiste em uma listagem de Criptomoedas obtidas da API [Coin Ranking](https://coinranking.com/), um sistema de votos onde o usuário pode atribuir notas às suas Criptomoedas favoritas e a opção de listar as moedas em ordem de popularidade.
## Stack utilizada

**Front-end:**
React e Typescript

**Estilização:**
Tailwind

**Backend:**
Python e Flask




## Demonstração
![GIF](assets/popularCoins.gif)




## Instalação

**1. Abra o terminal utlizando ("**ctrl+alt+t**") e crie um diretório no local de sua preferência com o comando **mkdir**, aqui neste exemplo usaremos o nome "**popularCoins**":**

```bash
  mkdir popularCoins
```
**2. Entre no diretório criado:**
```
  cd popularCoins
```
**3. Faça o clone do projeto utilizando a tag "--recursive" para clonar os submodulos:**
```
git clone --recursive https://github.com/omarcosdanilo/popular-coins.git

```
**Obs: esse comando irá criar um novo diretório contendo todos os módulos da aplicação!**

**4. Utilize o comando **"ls"** para verificar o nome do diretório criado:**
```
  ls
```
**5. Entre no diretório listado, usando o comando abaixo:**
```
  cd "nome do diretório"
```
**6. Entre no diretorio do backend:**
```
  cd "nome do diretório do backend"
```
**7. Crie o ambiente virtual do Python:**
```
python3 -m venv .venv 
```
**8. Ative o ambiente virtual:**
```
source .venv/bin/activate 
```
**9. Instale as dependências do backend:**
```
pip3 install -r requirements.txt  
```
**10. Inicie o servidor:**
```
python3 main.py && python3 server.py
```
**11. Retorno para o diretório principal:**
```
cd ..
```
**12. Entre no diretório do Frontend:**
```
cd "nome do diretório do Frontend"
```
**13. Instale as dependências do Frontend:**
```
npm install
```
**14. Inicie a aplicação:**
```
npm run dev
```

    