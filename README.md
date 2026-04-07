# Atividade-prof-alan
# CSS: Margin, Padding e Border

## 📌 Definição Geral
No CSS, *margin*, *padding* e *border* fazem parte do chamado **Box Model (modelo de caixa)**.  
Todo elemento HTML é representado como uma caixa composta por essas propriedades.

---

## 🧱 Border (Borda)

### 📖 Definição
A **border** é a borda que envolve o conteúdo e o padding de um elemento.

### 🔧 Propriedades principais
- `border-width`: espessura da borda
- `border-style`: estilo (solid, dashed, dotted, etc.)
- `border-color`: cor da borda

### 💡 Exemplo
```css
div {
  border: 2px solid black;
} 
```

# 🌐 Margin (Espaçamento Externo)

## 📖 Definição
A **margin** é o espaço fora da borda, separando um elemento dos outros.

## 🔧 Características
- Fica fora do elemento  
- Controla o espaçamento entre elementos  

## 💡 Exemplo
```css
div {
  margin: 20px;
}
```

## 🧠 Resumo Visual
[ margin ]
  [ border ]
    [ padding ]
      [ conteúdo ]
## ⚖️ Diferença rápida
Propriedade	Onde fica?	Função
margin	Fora da borda	Espaço entre elementos
border	Em volta	Define a borda do elemento
padding	Dentro da borda	Espaço interno do elemento
## 🚀 Dica prática

Se quiser visualizar melhor, use cores:

```css 
div {
  margin: 20px;
  border: 2px solid red;
  padding: 10px;
  background-color: lightgray;
}
```

## 🔗 Conclusão

Entender margin, padding e border é essencial para controlar o espaçamento e layout dos elementos em CSS.
