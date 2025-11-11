📝 Projeto: Formulário de Contato e Newsletter Simples e Responsivo
Este projeto demonstra a criação de um formulário de contato/inscrição para newsletter, seguindo as melhores práticas de HTML semântico e CSS focado em usabilidade e feedback visual.

O código foca em criar uma experiência limpa e moderna para o usuário, garantindo que o formulário seja o ponto central da página.

✨ Visão Geral e Destaques
O formulário é projetado para ser centralizado na tela, com um design de "cartão" que o destaca do fundo. O principal destaque do CSS é o tratamento dos campos de input para melhorar a usabilidade.

HTML Semântico: Utilização de <main>, <section>, <label> e attributes como id e name corretamente.

Centralização Perfeita: Uso de Flexbox (display: flex, justify-content: center, align-items: center) no body para centralizar o formulário vertical e horizontalmente.

Foco na Usabilidade (CSS): A aplicação do pseudo-seletor :focus nos campos de input garante que o usuário saiba exatamente onde está digitando, melhorando a acessibilidade e a experiência geral.

🛠️ Tecnologias Utilizadas
HTML5: Estrutura base e metadados (<meta name="viewport"> para responsividade e tags SEO).

CSS3: Estilização, layout Flexbox, e animações/transições suaves para o botão e campos de input.

📁 Estrutura do Projeto
Para que o projeto seja executado corretamente, a estrutura de pastas deve ser:

Projeto-Formulario-Simples/ ├── index.html ├── README.md (Este arquivo) ├── css/ │ └── style.css ├── assets/ └── logo.png (Favicon)
    
⚙️ Como Configurar
Baixe: Faça o download ou crie os arquivos index.html e style.css nas pastas corretas.

Assets: Certifique-se de que o arquivo logo.png esteja na pasta assets/.

Visualização: Abra o arquivo index.html no seu navegador. Recomenda-se o uso da extensão "Live Server" no VS Code para visualizar as alterações em tempo real.

🔍 Análise do Código (Foco em Usabilidade)
O bloco de CSS a seguir é o mais importante para a usabilidade e é um excelente exemplo de design user-friendly:

CSS

/* Realça o campo ativo (onde o usuário está digitando) */
.form-group textarea:focus,
.form-group input:focus {
    outline: none; /* Remove a borda feia padrão do navegador */
    border-color: #6a89cc; /* Muda a cor da borda para a cor primária */
    box-shadow: 0 0 0 3px rgba(106, 137, 204, 0.3); /* Adiciona uma "aura" de destaque */
}
Esta técnica garante que o formulário não apenas funcione, mas também seja agradável e intuitivo de preencher.

Criado por Vinicius Marques.
