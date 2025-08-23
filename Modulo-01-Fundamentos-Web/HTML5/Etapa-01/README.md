# 📘 Etapa 1 – Estrutura Básica de uma Página HTML

## 📖 Introdução
Todo site que você acessa na internet tem uma base em **HTML (HyperText Markup Language)**.  
O HTML é responsável por **estruturar o conteúdo** de uma página web, enquanto outras tecnologias (como CSS e JavaScript) cuidam do estilo e da interatividade.  

Nesta etapa, você vai aprender a **anatomia de um documento HTML** e como criar sua primeira página bem estruturada.

---

## 🧩 Estrutura Básica de um Documento HTML
A estrutura mínima de qualquer documento HTML5 é:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Descrição do meu site"> 
    <meta name="keywords" content="Palavras chaves de pesquisa">
    <title>Título da Página</title>
</head>
<body>
    <h1>Título do Site</h1>
    <p>Paragrafo do site, pode ser uma descrição, um texto, informação</p>
</body>
</html>
```

🔎 Explicação dos elementos

<!DOCTYPE html> → informa ao navegador que estamos usando HTML5, a versão mais atualizada e atual do HTML.

<html lang="pt-br"> → elemento raiz, indica o idioma da página.

<head> → contém metadados (informações que não aparecem no conteúdo, mas são importantes para o navegador e buscadores).

<meta charset="UTF-8"> → define o padrão de caracteres (UTF-8 suporta acentos e caracteres especiais).
<meta name="description" content="Descrição do meu site"> → Metadados onde define uma descrição para o site
<meta name="keywords" content="Palavras chaves de pesquisa"> → Metadados para definir as palavras chaves do site
<title> → define o título que aparece na aba do navegador.

<\head>

<body> → contém todo o conteúdo visível da página.

Dentro do body tem várias tags para criar a estrutura visual do site.

