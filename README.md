# 🌄 Exemplo de Lazy Load com HTML

Este projeto demonstra como utilizar o atributo `loading="lazy"` em imagens dentro de uma página HTML para melhorar a performance de carregamento.

## 🚀 O que é Lazy Load?

**Lazy Load**, ou carregamento preguiçoso, é uma técnica que adia o carregamento de recursos não críticos — como imagens — até que eles realmente sejam necessários. Em páginas web, isso significa que as imagens só serão carregadas quando estiverem próximas de aparecer na tela do usuário.

### ✅ Vantagens:
- Melhora o tempo de carregamento inicial da página
- Reduz o consumo de dados, especialmente em dispositivos móveis
- Melhora a performance percebida pelo usuário

## 📄 Estrutura do Projeto

Este é um simples documento HTML com imagens de personagens do anime Naruto que são carregadas sob demanda conforme o usuário rola a página.

### Principais componentes:
- **HTML5 Semântico**
- **CSS Puro para Estilização**
- Atributo `loading="lazy"` em todas as imagens

## 🖼️ Prévia do Conteúdo

As imagens utilizadas são:
- Naruto Uzumaki
- Sasuke Uchiha
- Kakashi Hatake

Elas estão configuradas com:
![image](https://github.com/user-attachments/assets/939a34dc-7467-47c8-b043-847c9b0ada68)

```html
<img 
  src="URL_DA_IMAGEM" 
  alt="Descrição da imagem" 
  loading="lazy" 
  width="800" 
  height="400"
/>


