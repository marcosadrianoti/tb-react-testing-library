# Projeto de testes com RTL - `React Testing Library`! :test_tube:
Projeto desenvolvido por mim durante o curso de Desenvolvimento Web na Trybe. Divulgado aqui como portfólio de aprendizado.

<details>
<summary><strong>Objetivos do projeto:</strong></summary>

  * Desenvolver testes para uma aplicação `React` que já está criada e configurada, utilizando `Jest` e a biblioteca `React Testing Library`.
  * Verificar se eu era capaz de:
    * Utilizar os seletores `queries` da `React-Testing-Library` em testes automatizados.
    * Simular eventos com a `React-Testing-Library` em testes automatizados.
    * Testar fluxos lógicos assíncronos com a `React-Testing-Library`.
    * Escrever testes que permitam a refatoração da estrutura dos componentes da aplicação sem necessidade de serem alterados.
    * Testar `inputs`.
</details>
<details>
<summary><strong> Requisitos do projeto:</strong></summary>

  * Criar o formulário que será usado para adicionar cartas ao baralho.
  * Adicionar as props necessárias ao componente de formulário.
  * Criar e renderize o componente Card com as props necessárias.
  * Criar o preview da carta que está sendo criada pelo formulário.
  * Fazer a validação do botão de Salvar no formulário.
  * Criar a função do botão salvar.
  * Criar a validação do Super Trunfo.
  * Exibir a lista de cartas que estão salvas no estado.
  * Criar um botão para remover uma carta do baralho.
  * Requisitos bônus:
    * Criar o filtro pelo nome da carta.
    * Criar o filtro por raridade da carta.
    * Criar o filtro de Super Trunfo.
</details>
  
## Rodando o projeto localmente

Para rodar o projeto em sua máquina, abra seu terminal, crie um diretório no local de sua preferência com o comando `mkdir` e acesse o diretório criado com o comando `cd`:

```bash
mkdir meu-diretorio &&
cd meu-diretorio
```

Clone o projeto com o comando `git clone`:

```bash
git clone git@github.com:marcosadrianoti/tb-tryunfo.git
```

Acesse o diretório do projeto com o comando `cd`:

```bash
cd tb-tryunfo
```

Instale as dependências executando:

```bash
npm install
```

Execute a aplicação:

```bash
npm run start
```

Para executar os testes:

```bash
npm test
``` 
