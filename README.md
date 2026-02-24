## **PROJETO 6: DESIGN DE COMMERCE**

### 📄 About (English)
**E-Commerce Conversion-Focused Website** - A fully functional online store prototype built with HTML5 and CSS3. Features persistent shopping cart with item counter, category navigation, promotional banner, product grids with discounts, pricing installments, star ratings, and newsletter signup. Implements CSS Grid for product layout, hover animations, and conversion-optimized CTAs. Perfect for e-commerce and marketplaces.

---

### 📚 README.md

```markdown
# 🛒 CommerceStore - Design de E-commerce

![Versão](https://img.shields.io/badge/versão-1.0.0-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![CSS Grid](https://img.shields.io/badge/CSS_Grid-products-FF6B6B)
![Conversão](https://img.shields.io/badge/foco-conversão-success)

## 📋 Sobre o Projeto

Este é um protótipo funcional de um site com **Design de Commerce**, desenvolvido a partir de um diagrama ASCII art. O projeto demonstra um layout focado em conversão, com categorias claras, carrinho sempre visível e elementos que incentivam a compra, típico de e-commerces e marketplaces.

### 🎯 Características do Design

- Header com logo, busca, carrinho persistente e login
- Categorias de produtos em destaque
- Banner promocional com chamadas para ação
- Grid de produtos com preços, descontos e parcelamento
- Seções: Ofertas do dia e Recomendados
- Newsletter para captura de leads
- Carrinho sempre visível com contador
- Foco em conversão e usabilidade

## 🏗️ Estrutura do Site

```
+--------------------------------------------------------------------+
| LOGO | BUSCA PRODUTOS... | CARRINHO | LOGIN                        |
+--------------------------------------------------------------------+
| CATEGORIAS: Eletrônicos | Moda | Casa | ...                        |
+--------------------------------------------------------------------+
|  BANNER PROMOCIONAL - GRANDE DESTAQUE                              |
|     [FRETE GRÁTIS] [OFERTAS]                                       |
+--------------------------------------------------------------------+
|                                                                    |
|  OFERTAS DO DIA:                                                   |
|  +-------+  +-------+  +-------+  +-------+                        |
|  | PROD  |  | PROD  |  | PROD  |  | PROD  |                        |
|  | 1     |  | 2     |  | 3     |  | 4     |                        |
|  | R$99  |  | R$149 |  | R$79  |  | R$199 |                        |
|  +-------+  +-------+  +-------+  +-------+                        |
|                                                                    |
|  RECOMENDADOS PARA VOCÊ:                                           |
|  +-------+  +-------+  +-------+                                   |
|  | PROD  |  | PROD  |  | PROD  |                                   |
|  | 5     |  | 6     |  | 7     |                                   |
|  +-------+  +-------+  +-------+                                   |
|                                                                    |
+--------------------------------------------------------------------+
|  NEWSLETTER: [EMAIL] [ASSINAR]                                     |
+--------------------------------------------------------------------+
```

## ✨ Funcionalidades Implementadas

### Header (Foco em Conversão)

- ✅ **Logo** "CommerceStore" com gradiente vermelho-turquesa
- ✅ **Busca** com campo de texto e botão estilizado
- ✅ **Carrinho sempre visível** com ícone e contador (3 itens)
- ✅ **Login** com ícone e texto "Entrar"
- ✅ Efeitos hover em todos elementos

### Categorias

- ✅ 6 categorias principais: Eletrônicos, Moda, Casa, Esportes, Livros, Games
- ✅ Efeito hover com underline vermelho
- ✅ Todas clicáveis com feedback visual
- ✅ Destaque "CATEGORIAS:" em vermelho

### Banner Promocional

- ✅ Gradiente turquesa-vermelho
- ✅ Título "SUPER OFERTAS DA SEMANA" (42px)
- ✅ 3 tags: "FRETE GRÁTIS", "OFERTAS IMPERDÍVEIS", "ATÉ 50% OFF"
- ✅ Efeito glassmorphism nas tags
- ✅ Sombra para destacar

### Seção: Ofertas do Dia

- ✅ Título com ícone 🔥 e contador "4 produtos"
- ✅ 4 produtos com:
  - Imagem representativa (📱, 👕, 🎧, ⌚)
  - Tag de desconto (-30%, -20%, -40%, -15%)
  - Preço com desconto e preço original riscado
  - Parcelamento (ex: "12x de R$ 9,90")
  - Avaliação com estrelas e número de reviews
  - Botão "Adicionar" em vermelho

### Seção: Recomendados para Você

- ✅ Título com ícone 🎯 e contador "3 produtos"
- ✅ 3 produtos adicionais:
  - Notebook, Câmera, Console
  - Preços cheios (sem desconto)
  - Parcelamento correspondente
  - Altas avaliações (★★★★★)

### Produtos - Detalhamento Completo

| # | Produto | Imagem | Preço | Desconto | Parcelamento | Avaliação |
|---|---------|--------|-------|----------|--------------|-----------|
| 1 | Smartphone Galaxy A15 | 📱 | R$ 99 | -30% | 12x R$ 9,90 | ★★★★☆ (127) |
| 2 | Camisa Social Slim | 👕 | R$ 149 | -20% | 6x R$ 24,83 | ★★★★★ (89) |
| 3 | Fone Bluetooth | 🎧 | R$ 79 | -40% | 5x R$ 15,80 | ★★★☆☆ (42) |
| 4 | Smartwatch Sport | ⌚ | R$ 199 | -15% | 10x R$ 19,90 | ★★★★☆ (210) |
| 5 | Notebook Ultra i5 | 💻 | R$ 2.499 | - | 12x R$ 208,25 | ★★★★★ (341) |
| 6 | Câmera DSLR | 📷 | R$ 1.899 | - | 10x R$ 189,90 | ★★★★☆ (156) |
| 7 | Console Game | 🎮 | R$ 2.999 | - | 12x R$ 249,90 | ★★★★★ (528) |

### Newsletter

- ✅ Título "📧 NEWSLETTER" com subtítulo
- ✅ Campo de email com placeholder
- ✅ Botão "ASSINAR" em vermelho
- ✅ Layout responsivo (empilha no mobile)

### Rodapé

- ✅ Links institucionais (Sobre, Privacidade, Trocas, Atendimento, Trabalhe conosco)
- ✅ Ícones de pagamento (💳 💵 📦 🚚)
- ✅ Contato (email e telefone)
- ✅ Copyright

### Interatividade

- ✅ Todos produtos clicáveis (card inteiro)
- ✅ Botões "Adicionar" com alerta personalizado
- ✅ Carrinho clicável com alerta e contador
- ✅ Login clicável
- ✅ Categorias com alerta
- ✅ Newsletter com alerta de inscrição
- ✅ Links do rodapé com alertas

## 🎨 Paleta de Cores

| Cor | Hexadecimal | Uso |
|-----|-------------|-----|
| Vermelho | `#ff6b6b` | Botões, preços, badges, hover |
| Vermelho Escuro | `#ff5252` | Hover dos botões |
| Turquesa | `#4ecdc4` | Gradiente do banner |
| Azul Escuro | `#1e293b` | Newsletter, textos |
| Azul Mais Escuro | `#0f172a` | Rodapé |
| Cinza Claro | `#f8fafc` | Fundo de elementos |
| Cinza Médio | `#94a3b8` | Textos secundários |
| Amarelo | `#fbbf24` | Estrelas de avaliação |

## 📱 Responsividade

O layout se adapta perfeitamente:

- **Desktop:** Grid de 4 colunas nas ofertas, 3 nos recomendados
- **Tablet:** Grid de 2-3 colunas dependendo da largura
- **Mobile (< 768px):**
  - Header em coluna
  - Grid de 2 colunas para produtos
  - Newsletter empilhada
  - Categorias em wrap

## 🔗 Links e Navegação

| Elemento | Ação (alerta) |
|----------|---------------|
| Botão Buscar | "Buscando produtos..." |
| Carrinho | "Carrinho de compras - 3 itens" |
| Login | "Página de login / cadastro" |
| Categorias (6) | Nome da categoria (ex: "Eletrônicos") |
| Produto (card) | (navegação para produto) |
| Botão Adicionar | "Produto adicionado: [nome]" |
| Newsletter Assinar | "Inscrição realizada com sucesso!" |
| Links rodapé | Nome da seção |

## 🚀 Como Executar

1. Clone este repositório
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. Navegue pelos produtos e categorias
4. Teste o carrinho e os botões de compra
5. Redimensione para ver a responsividade

## 💻 Tecnologias Utilizadas

- **HTML5 semântico** - Estrutura de e-commerce
- **CSS3 Avançado:**
  - **CSS Grid** para layout de produtos (`grid-template-columns: repeat(auto-fit, minmax(220px, 1fr))`)
  - **Flexbox** para header, categorias e newsletter
  - **Gradientes lineares** no banner e logo
  - **Transitions** para hovers suaves
  - **Box shadows** para profundidade
  - **Border-radius** para cards arredondados
  - **Media queries** para responsividade
- **JavaScript mínimo** - Alertas interativos
- **Design System** - Consistência visual em todos elementos

## 📊 Elementos de Conversão

| Elemento | Propósito |
|----------|-----------|
| Carrinho sempre visível | Facilita finalização da compra |
| Contador no carrinho | Urgência e lembrança |
| Tags de desconto | Atrair atenção para ofertas |
| Preço parcelado | Reduz barreira de compra |
| Avaliações com estrelas | Prova social |
| Botão "Adicionar" em destaque | Call-to-action claro |
| Recomendados | Cross-selling |
| Newsletter | Captura de leads |

## 📌 Casos de Uso

Este template é ideal para:
- **E-commerces** - Lojas virtuais completas
- **Marketplaces** - Múltiplos vendedores
- **Lojas de nicho** - Especializadas em categorias
- **Dropshipping** - Catálogos de produtos
- **Promoções relâmpago** - Ofertas do dia
- **Black Friday** - Landing pages promocionais

## 🧩 Diferenciais

- ✅ **Carrinho persistente** com contador em tempo real
- ✅ **Grid responsivo** que se adapta automaticamente
- ✅ **Tags de desconto** em todos produtos promocionais
- ✅ **Preço parcelado** para incentivar compras
- ✅ **Duas seções de produtos** (ofertas + recomendados)
- ✅ **Banner promocional** com 3 chamadas
- ✅ **Newsletter integrada** no final
- ✅ **ASCII art demonstrativo** no topo

## 🧪 Validação do ASCII Art

| Elemento ASCII | Implementação |
|----------------|---------------|
| LOGO | ✅ CommerceStore com gradiente |
| BUSCA PRODUTOS... | ✅ Campo de busca com placeholder |
| CARRINHO | ✅ Ícone com contador "3" |
| LOGIN | ✅ Ícone + texto "Entrar" |
| CATEGORIAS | ✅ 6 categorias clicáveis |
| BANNER PROMOCIONAL | ✅ Título + tags [FRETE GRÁTIS] [OFERTAS] |
| OFERTAS DO DIA (4 produtos) | ✅ 4 produtos com preços R$99, R$149, R$79, R$199 |
| RECOMENDADOS (3 produtos) | ✅ 3 produtos adicionais |
| NEWSLETTER | ✅ Campo email + botão ASSINAR |

## 👨‍💻 Autor

Desenvolvido como demonstração de design de e-commerce baseado em diagrama ASCII art por Daniel Gehlen.

---

## 📝 Notas de Versão

### v1.0.0 (24/02/2026)

- ✅ Implementação completa do design ASCII art
- ✅ Header com logo, busca, carrinho (contador) e login
- ✅ 6 categorias de produtos
- ✅ Banner promocional com 3 tags
- ✅ 7 produtos no total (4 ofertas + 3 recomendados)
- ✅ Todos produtos com preço, parcelamento e avaliação
- ✅ Newsletter funcional
- ✅ Rodapé com links e formas de pagamento
- ✅ Design responsivo completo
- ✅ Todos elementos clicáveis

### Próximas Melhorias (Sugestões)

- [ ] Carrinho funcional com localStorage
- [ ] Página de produto individual
- [ ] Filtros por preço e categoria
- [ ] Sistema de busca real
- [ ] Modal de produto rápido
- [ ] Integração com API de pagamentos

---

**📅 Última atualização:** 24 de Fevereiro de 2026
