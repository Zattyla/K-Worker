# Idol Studio | K-Pop Agency Manager

Bem-vindo ao **Idol Studio**, um web app completo criado para simular o gerenciamento e a criação de grupos de uma agência de K-pop. 

> **Nota de Desenvolvimento:** Todo o design, lógica e programação deste projeto foram desenvolvidos **100% através de um celular**, provando que é possível criar aplicações complexas e bonitas diretamente da palma da mão.

---

## Funcionalidades

O sistema é dividido em 7 departamentos interligados, utilizando um design moderno com *Glassmorphism*, tons pastéis e suporte nativo a **Dark Mode**.

* **Dashboard (`index.html`):** Painel de controle da agência com To-Do List integrada e um sistema vital de **Backup/Restauração** global via código de segurança.
* **Gerador Inteligente (`gerador.html`):** O "cérebro" da agência. Sintetiza novos idols cruzando dados aleatórios com referências de artistas reais (Face e Voice Claims, respeitando o gênero) e gerando status no estilo RPG (Vocal, Dança, Presença).
* **Banco de Talentos (`galeria.html`):** Lista de todos os artistas agenciados. Permite visualizar dados técnicos, copiar a ficha do idol ou demiti-lo.
* **Debut Simulator (`grupos.html`):** Ferramenta de formação. Selecione a quantidade de membros, o gênero (Masculino, Feminino ou Misto) e o conceito. O sistema sorteia os idols e distribui os cargos oficiais do grupo automaticamente (Líder, Maknae, Main Vocal, etc.).
* **Portfólio (`portfolio.html`):** Exibe todos os grupos oficiais da empresa de forma detalhada e organizada.
* **Comebacks (`comebacks.html`):** Departamento de planejamento de lançamentos. Escolha o grupo, o nome do álbum, a Title Track e o estilo de direção do MV.
* **Moodboard (`fotos.html`):** Ferramenta para anexar links de imagens (Pinterest, Google) aos seus idols salvos, criando referências visuais reais para o projeto.

---

## Tecnologias Utilizadas

* **HTML5 & CSS3:** Estruturação e estilização (UI responsiva focada em Mobile-First, Flexbox e CSS Grid).
* **JavaScript (Vanilla):** Lógica de sorteio, manipulação da DOM e sistema de backup em JSON.
* **Local Storage (API do Navegador):** Banco de dados interno do navegador para comunicação e persistência de dados entre as múltiplas páginas (Zero Back-end).

---

## ⚠️ Como Usar

Como o projeto utiliza o `localStorage` para salvar os dados, **nenhuma instalação é necessária**. Tudo acontece no seu próprio navegador!

1. Acesse o link oficial do projeto pelo **GitHub Pages**.
2. Crie seus primeiros artistas no **Gerador**.
3. Vá para a página de **Grupos** para montar sua primeira lineup.
4. **IMPORTANTE:** Navegadores de celular podem apagar o cache de vez em quando. Use sempre o botão de **"Gerar Código"** na tela de *Dashboard* para fazer backup de todo o seu progresso em texto!

---

Desenvolvido com amor e muita paciência.
