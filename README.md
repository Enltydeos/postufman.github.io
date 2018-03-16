<script src="https://cdnjs.cloudflare.com/ajax/libs/markdown.js/0.5.0/markdown.min.js"></script>
<article></article>



const message = `
# markdown





[I'm a relative reference](testMarkDown.md)
`;

const article = document.querySelector('article');
article.innerHTML = markdown.toHTML(message);
