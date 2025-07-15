# HTML - Seu Primeiro Código (Cap. 04 - Aula 02)

Created: 14 de julho de 2025 16:05
Matéria: Programação

TEMA: Introdução ao HTML e seu primeiro código.

  O que é HTML?

- HTML significa HyperText Markup Language (Linguagem de Marcação de Hipertexto).
- É a linguagem padrão para a criação de páginas web.
- Não é uma linguagem de programação, mas sim uma linguagem de marcação. Isso significa que ela usa "tags" para definir a estrutura e o conteúdo de uma página.
- O HTML é responsável por organizar o conteúdo da web (textos, imagens, links, vídeos, etc.).
1. Estrutura Básica de um Documento HTML
Todo documento HTML segue uma estrutura fundamental que define como o navegador deve interpretá-lo.
- <!DOCTYPE html>:
    - Declaração de documento.
    - Sempre a primeira linha de um documento HTML.
    - Informa ao navegador qual versão do HTML está sendo usada (neste caso, HTML5).
    - Crucial para que o navegador renderize a página corretamente no modo padrão.
- <html lang="pt-br">...</html>:
    - Elemento raiz de toda a página HTML. Tudo o que está na página (exceto o <!DOCTYPE>) deve estar dentro desta tag.
    - O atributo lang="pt-br" define o idioma principal do conteúdo da página (aqui, português do Brasil). Isso é importante para acessibilidade (leitores de tela) e SEO.
- <head>...</head>:
    - Contém metadados sobre a página, ou seja, informações que não são exibidas diretamente no navegador para o usuário, mas são importantes para o funcionamento e a otimização da página.
    - Exemplos de metadados comuns:
        - <meta charset="UTF-8">: Define o conjunto de caracteres do documento. UTF-8 é o mais recomendado, pois suporta a maioria dos caracteres e símbolos do mundo, incluindo acentos e caracteres especiais. Essencial para evitar problemas de exibição de caracteres.
        - <meta name="viewport" content="width=device-width, initial-scale=1.0">: Configura a visualização em dispositivos móveis. Garante que a página se ajuste à largura do dispositivo e tenha uma escala inicial adequada. Fundamental para o design responsivo.
        - <title>...</title>: Define o título da página, que aparece na aba do navegador, nos favoritos e nos resultados de busca. Ponto chave para SEO e usabilidade.
        - Links para folhas de estilo CSS (<link rel="stylesheet" href="style.css">).
        - Links para arquivos JavaScript (<script src="script.js"></script>).
- <body>...</body>:
    - Contém todo o conteúdo visível da página para o usuário.
    - Tudo o que você vê em um site (textos, imagens, vídeos, botões, formulários, etc.) é colocado dentro da tag <body>.
    

  Sintaxe Básica das Tags HTML

- HTML utiliza tags para marcar elementos.
- A maioria das tags tem uma tag de abertura e uma tag de fechamento.
    - Ex: <p> (abertura) e </p> (fechamento) para um parágrafo.
    - O conteúdo fica entre as tags: <p>Este é um parágrafo.</p>
- Algumas tags são autofechantes (ou "vazias" / "void elements"), ou seja, não precisam de uma tag de fechamento porque não contêm conteúdo.
    - Ex: <br> (quebra de linha), <img> (imagem), <input> (campo de entrada).
- Atributos: Fornecem informações adicionais sobre um elemento. São colocados na tag de abertura e geralmente seguem o formato nome="valor".
    - Ex: <a href="[https://www.google.com](https://www.google.com/)">Link para o Google</a> (onde href é o atributo e "[https://www.google.com](https://www.google.com/)" é o seu valor).
    

Exemplo de "Seu Primeiro Código HTML" (Estrutura Mínima)
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Minha Primeira Página HTML</title>
</head>
<body>
<h1>Olá, Mundo!</h1>
<p>Esta é a minha primeira página web.</p>
<p>Estou aprendendo HTML!</p>
</body>
</html>

Explicação do Exemplo:

- <h1>Olá, Mundo!</h1>: Define um título principal (cabeçalho de nível 1). <h1> é a tag para o maior nível de cabeçalho, indo até <h6> (o menor).
- <p>...</p>: Define um parágrafo de texto.

 Como Visualizar seu Código HTML

- Crie um arquivo: Abra um editor de texto simples (como Bloco de Notas no Windows, TextEdit no Mac, ou editores mais avançados como VS Code, Sublime Text, Atom).
- Digite o código HTML no arquivo.
- Salve o arquivo com a extensão .html (ex: index.html, minhapagina.html).
- Abra o arquivo no navegador: Basta dar um clique duplo no arquivo salvo, e ele será aberto automaticamente no seu navegador padrão (Chrome, Firefox, Edge, etc.).

 Pontos Importantes para Memorização

- HTML = Estrutura e Conteúdo.
- <!DOCTYPE html> e a tag <html> são o esqueleto da página.
- <head> = Informações para o navegador (metadados, título, links para CSS/JS).
- <body> = Conteúdo visível para o usuário.
- Tags de abertura/fechamento vs. tags autofechantes.
- Atributos fornecem detalhes extras.
- charset="UTF-8": Sempre usar para evitar problemas com caracteres.
- viewport: Essencial para responsividade.
- title: Muito importante para SEO e identificação da página.
Próximos Passos (Aula 03 - Tópicos Implícitos):
- Aprofundar em mais tags HTML (links, imagens, listas, etc.).
- Introdução ao CSS para estilização (como visto no logo "HTML5 & CSS3" na imagem).