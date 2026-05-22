# Javascript Curso em Vídeo

Projeto de estudo em **JavaScript**, **HTML5** e **CSS3**, desenvolvido com base nos exercícios do **Curso em Vídeo**.

O repositório contém um **verificador de idade**, onde o usuário informa o ano de nascimento e seleciona o sexo. Com essas informações, o JavaScript calcula a idade aproximada, identifica a categoria visual correspondente e exibe uma imagem relacionada.

## Sobre o projeto

O `javascript01` é um exercício prático para treinar manipulação do DOM, eventos, validação simples de dados e alteração dinâmica do conteúdo da página.

A aplicação permite:

- Digitar o ano de nascimento;
- Escolher entre masculino e feminino;
- Clicar no botão “Verificar”;
- Calcular a idade com base no ano atual;
- Exibir uma mensagem personalizada;
- Mostrar uma imagem correspondente à faixa etária e ao sexo selecionado.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript

## Estrutura do repositório

```text
javascript01/
├── .gitattributes
├── LICENSE
├── ex002.html
├── homem.png
├── jovem.png
├── menina.png
├── menino.png
├── moca.png
├── mulher.png
├── script.js
├── senhor.png
├── senhora.png
└── style.css
```

## O que tem dentro

### `ex002.html`

Arquivo principal da página. Ele contém:

- Título do exercício;
- Campo para informar o ano de nascimento;
- Botões de seleção de sexo;
- Botão para executar a verificação;
- Área de resultado;
- Importação do arquivo `script.js`.

### `script.js`

Arquivo responsável pela lógica da aplicação. Ele:

- Obtém o ano atual;
- Lê o ano informado pelo usuário;
- Valida se o campo foi preenchido corretamente;
- Calcula a idade;
- Verifica o sexo selecionado;
- Define uma imagem de acordo com a idade e o sexo;
- Exibe o resultado na tela.

### `style.css`

Arquivo de estilos da página. Ele define:

- Cor de fundo;
- Fonte da página;
- Card central;
- Sombra;
- Alinhamento do resultado;
- Estilo do rodapé.

### Imagens

O projeto possui imagens usadas para representar diferentes faixas etárias:

- `menino.png`
- `menina.png`
- `jovem.png`
- `moca.png`
- `homem.png`
- `mulher.png`
- `senhor.png`
- `senhora.png`

## Como executar o projeto

1. Baixe ou clone este repositório:

```bash
git clone https://github.com/thamiscoder/javascript01.git
```

2. Acesse a pasta do projeto:

```bash
cd javascript01
```

3. Abra o arquivo `ex002.html` no navegador.

Também é possível executar usando a extensão **Live Server** no Visual Studio Code.

## Como usar

1. Informe o ano de nascimento.
2. Selecione o sexo.
3. Clique em **Verificar**.
4. Veja a idade calculada e a imagem correspondente.

## Aprendizados praticados

- Manipulação do DOM;
- Uso de `getElementById`;
- Uso de `querySelector`;
- Uso de `getElementsByName`;
- Eventos com `onclick`;
- Condicionais `if` e `else`;
- Criação dinâmica de elementos com JavaScript;
- Alteração de atributos com `setAttribute`;
- Validação simples de entrada;
- Exibição dinâmica de resultados.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.
