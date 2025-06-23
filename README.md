# 🌳 Árvore Binária de Pesquisa (BST) em Java

Este projeto, desenvolvido para a disciplina de Estruturas de Dados I, é uma implementação em Java de uma **Árvore Binária de Pesquisa (BST)**. A aplicação lê uma sequência de números inteiros de um arquivo, constrói a árvore e realiza diversas operações, salvando os resultados em arquivos de texto.

-----

## ✨ Funcionalidades

  - **Construção da Árvore:** Insere valores inteiros de um arquivo `arquivo.txt`, construindo a BST na ordem em que aparecem.
  - **Chave de Busca:** Utiliza a última linha do arquivo de entrada como a chave de busca, **não inserindo** este valor na árvore.
  - **Caminhamentos:** Realiza e salva quatro tipos de caminhamento em arquivos `.txt` separados:
      - Pré-ordem (`preordem.txt`)
      - Pós-ordem (`posordem.txt`)
      - Central (in-order) (`central.txt`)
      - Por Largura (`largura.txt`)
  - **Busca Detalhada:** Procura a chave na árvore e gera um relatório (`resultado.txt`) com o caminho de nós visitados, a quantidade de visitas e se a chave foi encontrada.

-----

## 📂 Estrutura do Projeto

```
/
├── App.java                   # Classe principal com a lógica da aplicação
├── ArvoreBinariaPesquisa.java # Implementação da Árvore Binária de Pesquisa
├── arquivo.txt                # Arquivo de entrada com os valores a serem inseridos
│
├── preordem.txt               # (Saída) Caminhamento em pré-ordem
├── posordem.txt               # (Saída) Caminhamento em pós-ordem
├── central.txt                # (Saída) Caminhamento em ordem central
├── largura.txt                # (Saída) Caminhamento por largura
└── resultado.txt              # (Saída) Resultado da busca pela chave
```

-----

## 🚀 Como Executar

### Pré-requisitos

  - É necessário ter o **Java Development Kit (JDK)** instalado no seu sistema.

### Passos

1.  **Clone o repositório:**

    ```bash
    git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
    cd SEU_REPOSITORIO
    ```

2.  **Prepare o arquivo de entrada:**

      - Crie um arquivo chamado `arquivo.txt` no mesmo diretório do projeto.
      - Adicione os números inteiros, um por linha.
      - Lembre-se: a **última linha** será a chave de busca e não será inserida na árvore.

    *Exemplo (`arquivo.txt`):*

    ```
    50
    30
    70
    20
    40
    60
    80
    40  <-- Esta será a chave de busca
    ```

3.  **Compile e execute o código:**
    Abra o terminal no diretório do projeto e execute os seguintes comandos:

    ```bash
    # 1. Compile os arquivos Java
    javac App.java ArvoreBinariaPesquisa.java

    # 2. Execute a aplicação
    java App
    ```

4.  **Verifique os resultados:**
    Após a execução, os arquivos `preordem.txt`, `posordem.txt`, `central.txt`, `largura.txt` e `resultado.txt` serão gerados no diretório com as saídas correspondentes.

-----

## 👨‍💻 Autores

  - **Samantha Martins**
  - **Júnior Fernando Stahl**
  - **Maria Melloni**

*Trabalho apresentado na disciplina de Estruturas de Dados I, ministrada pelo professor Leonardo Heredia.*
