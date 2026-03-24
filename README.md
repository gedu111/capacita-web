
body {
    margin: 0;
    font-family: Arial, sans-serif; /* muda a fonte do site inteiro */
}

header {
    display: flex;              /* coloca os elementos lado a lado */
    justify-content: space-between; /* separa logo e menu */
    align-items: center;        /* centraliza verticalmente */

    padding: 20px 40px;
    background-color: #f4f4f4;  /* cor de fundo */
}

.logo img {
    height: 60px;
}


/* Menu de navegação */
nav a {
    margin-left: 20px;
    text-decoration: none;  /* remove sublinhado do link */
    color: #4b2e83;         /* cor do texto */
    font-weight: bold;
}


.pagina {
    padding: 40px;
}


/* Título da página */
.topo h2 {
    font-size: 32px;
    color: #4b2e83;
}


/* Texto e imagem lado a lado */
.conteudo {
    display: flex;
    align-items: center;
    gap: 40px; /* espaço entre texto e imagem */
}


/* Parágrafos */
.texto p {
    font-size: 18px;
    line-height: 1.6; /* espaçamento entre linhas */
}


/* Imagem do robô */
.imagem img {
    width: 350px;
}


.informacoes {
    margin-top: 40px;
}


.informacoes h3 {
    color: #4b2e83;
}


.informacoes ul {
    margin-top: 10px;
}


.informacoes li {
    margin-bottom: 8px;
}

.acao {
    margin-top: 40px;
}


button {
    background-color: #4b2e83;
    color: white;

    padding: 12px 24px;
    border: none;

    font-size: 16px;
    cursor: pointer;
}


/* efeito quando passa o mouse */
button:hover {
    background-color: #372261;
}