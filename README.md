#   

##
* **Nome:** Mateus Jhonata  
* **Curso:** Análise e Desenvolvimento de Sistemas (ADS)  
* **Data:** 07 de abril de 2026

---

## 📝 Definições, Usos e Exemplos

Nesta atividade, apresento os três pilares que definem o tamanho e o espaçamento de qualquer elemento em uma página web: **Margin**, **Padding** e **Border**.

### 1. Margin (Margem)
**Definição:** A `margin` é o espaço **externo** ao redor de um elemento. Ela serve para criar distância entre o elemento atual e os outros ao seu redor.
* **Uso:** Utilizada para separar blocos de conteúdo, criar respiros no layout e centralizar elementos na tela.
* **Exemplo de Código:**
    ```css
    .caixa-externa {
      margin: 30px; /* Afasta o elemento 30px de todos os lados vizinhos */
    }
    ```

### 2. Padding (Preenchimento)
**Definição:** O `padding` é o espaço **interno** de um elemento. Ele fica localizado entre o conteúdo (texto ou imagem) e a sua borda.
* **Uso:** Serve para dar conforto visual ao conteúdo, impedindo que ele "encoste" nas paredes da caixa. O padding assume a cor de fundo do elemento.
* **Exemplo de Código:**
    ```css
    .cartao-conteudo {
      padding: 20px; /* Cria um respiro interno de 20px para o texto */
    }
    ```

### 3. Border (Borda)
**Definição:** A `border` é a linha que envolve o conteúdo e o padding. Ela é o limite visual que separa o "dentro" do "fora" do elemento.
* **Uso:** Utilizada para destacar elementos, criar divisórias ou definir visualmente o tamanho de botões e campos de formulário.
* **Exemplo de Código:**
    ```css
    .borda-destaque {
      border: 2px solid #007bff; /* Linha azul sólida de 2 pixels */
    }
    ```
