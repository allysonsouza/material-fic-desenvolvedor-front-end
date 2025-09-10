# 2. Minha primeira página web

## 📄 Estrutura mínima do HTML:

```html
<!doctype html>
<html>
  <head>
  </head>
  <body>
  </body>
</html>
```

### 1. `<!doctype html>`

- **O que é?** É uma **declaração**, não uma tag.
- **Função:** Informa ao navegador que este é um documento HTML na **versão 5** (HTML5), que é a mais usada atualmente.
- **Importância:** Ajuda os navegadores a interpretarem corretamente o código HTML.
- **Obs:** Não tem "tag de fechamento". É usada apenas no topo da página.

---

### 2. `<html> ... </html>`

- **O que é?** A **tag raiz** de todo documento HTML.
- **Função:** Envolve **todo o conteúdo** da página (incluindo `<head>` e `<body>`).
- **Atributo comum (opcional):** Pode incluir `lang`, que indica o idioma do conteúdo (ex: `<html lang="pt-br">` para português do Brasil).

---

### 3. `<head> ... </head>`

- **O que é?** Uma seção especial da página que **não é exibida diretamente** na tela do navegador.
- **Função:** Armazena **informações sobre a página**, como:
    - Título da aba do navegador (`<title>`)
    - Links para arquivos de estilo (CSS)
    - Metadados (ex: codificação de caracteres, descrição)
    - Scripts que controlam comportamentos da página (JavaScript)
- **Exemplo de conteúdo do `<head>`:**
    
    ```html
    <head>
      <meta charset="UTF-8">
      <title>Minha Página</title>
    </head>
    ```
    

---

### 4. `<body> ... </body>`

- **O que é?**
    
    A seção onde vai todo o **conteúdo visível da página**.
    
- **Função:**
    
    Aqui vão os textos, imagens, botões, links, vídeos e tudo o que o usuário verá e interagirá.
    
- **Exemplos de conteúdo que ficam no `<body>`:**
    
    ```html
    <body>
      <h1>Bem-vindo!</h1>
      <p>Este é meu primeiro site.</p>
      <img src="imagem.jpg" alt="Exemplo de imagem">
    </body>
    ```
    

---

## 🧠 Resumo visual

| Tag | Função principal |
| --- | --- |
| `<!doctype html>` | Diz ao navegador que estamos usando HTML5 |
| `<html>` | Envolve toda a estrutura da página |
| `<head>` | Guarda informações sobre a página (não visível ao usuário) |
| `<body>` | Contém tudo que o usuário vê na tela |