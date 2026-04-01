# 📱 A Galeria que não Quebra | Teste de Responsividade

Este repositório contém um exercício prático focado em **Design Responsivo**. O objetivo do projeto é demonstrar visualmente e no código a diferença entre layouts com dimensões fixas e layouts fluidos, garantindo que a interface se adapte a qualquer tamanho de tela sem "quebrar" ou esconder elementos.

Como exemplo visual, o projeto traz uma galeria temática de automobilismo, exibindo cards fluidos com carros de alta performance e da Fórmula 1.

## 🎯 Objetivo da Atividade

A transição de telas de desktop para dispositivos móveis exige que os elementos de uma página web sejam flexíveis. Esta atividade explora:
* O comportamento de containers `fixos` (medidas absolutas, como `px`) versus containers `fluidos` (medidas relativas, como `%`).
* A implementação de **CSS Flexbox** para alinhar e distribuir os elementos de forma dinâmica.
* O uso de **Media Queries** (`@media`) para alterar completamente a estrutura dos cards quando a tela atinge um tamanho específico (ex: `max-width: 600px`).

---

## 🛠️ Instruções do Exercício

Para replicar "A Galeria que não Quebra", os seguintes passos e regras técnicas foram aplicados:

1. **Estrutura Base:**
   * Criar uma seção contendo 3 "cards".
   * Cada card deve conter uma imagem (foto) e um texto de legenda.
2. **Regra Técnica (CSS):**
   * Os cards não podem ter larguras fixas em pixels. 
   * É obrigatório o uso de porcentagens para a largura, distribuindo os itens no container principal (ex: `width: 30%`).
   * As imagens dentro dos cards devem ser configuradas para não vazar o limite do bloco (`width: 80%` ou `100%`, com `display: block`).
3. **Validação e Testes:**
   * Abrir o projeto no navegador.
   * Acessar o **Console do Desenvolvedor** (F12).
   * Clicar no ícone de **"Dispositivos Móveis"** (Device Toolbar).
   * Testar a responsividade simulando as telas de um **iPhone** e de um **Samsung Galaxy**, observando como os cards passam de 3 colunas para 1 coluna empilhada (`width: 100%`) nas telas menores.

---

## 💻 Tecnologias Utilizadas

* **HTML5:** Estruturação semântica da galeria.
* **CSS3:** Estilização com Flexbox (`display: flex`, `flex-wrap: wrap`, `gap`), controle de overflow e Media Queries.

---

# 📂 Como executar o projeto
1. Clone este repositório:
```bash
(git clone [https://github.com/yago-molina/AtividadeFixo-Fluido.git])
