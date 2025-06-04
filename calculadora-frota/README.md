# Calculadora de Frotas – Ikariam

Este aplicativo em Java (com interface Swing) foi criado para ajudar jogadores de Ikariam a calcular custos, população e manutenção das unidades navais do jogo de forma automatizada e visual.

---

## ⚙️ Como funciona

Cada unidade naval (como *Lança-chamas*, *Aríete a vapor*, *Reparadores*, etc.) possui funções e valores distintos no jogo, como:

- **Linha de frente**
- **Flanco**
- **Artilharia**
- **Suporte**

Cada unidade tem:
- **Pontos de generais**
- **Custo de manutenção (parado e em movimento)**
- **Custo de produção (madeira, enxofre, cristal)**
- **População necessária**
- **Valor de mercado no Mercado Negro (MN)**

---

## 🧮 Cálculos realizados

### 🔹 Pontos de Generais
Exemplo:
- 1 *Lança-chamas* = 6,2 pontos
- 1 *Aríete a vapor* = 24 pontos  
O total é atualizado automaticamente conforme a quantidade de unidades inserida.

### 🔹 Manutenção
- **Parados:** manutenção base por unidade.
- **Em movimento:** manutenção dobrada.
- **Lvl do Futuro:** cada nível reduz 2% de manutenção (acumulativo).

### 🔹 Recursos necessários
Cada unidade consome:
- **Madeira**
- **Enxofre**
- **Cristal** (algumas unidades)

### 🔹 Reduções por Edifícios
- **Carpintaria**: -1% por nível no custo de madeira.
- **Pirotecnia**: -1% por nível no custo de enxofre.
- **Oculista**: -1% por nível no custo de cristal.  
Máximo: **nível 50** para cada prédio (até 50% de desconto).

### 🔹 População
- Ex: *Lança-chamas* requer 4 cidadãos por unidade.
- Total de população usada é somada.
- **População por cidade** ajuda a dividir a produção igualmente:
  > Ex: 24k população total / 12 cidades = 2k cidadãos livres por cidade.

### 🔹 Ouro no Mercado Negro
Cada unidade tem um valor de compra/venda.  
O app calcula o **ouro necessário** para comprar todas as unidades desejadas.

---

## 🎥 Demonstração

📁 Arquivo `demo.mp4` incluído nesta pasta com vídeo de 1 minuto mostrando o funcionamento da calculadora.

---

## ❗ Observação

O código-fonte não está disponível neste repositório. Este app foi feito como um projeto pessoal e demonstrativo.
