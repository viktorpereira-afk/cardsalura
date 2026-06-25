<div class="tech-card-container">
  
  <article class="tech-card">
    <div class="card-image">
      <img src="https://via.placeholder.com/400x250" alt="Inteligência Artificial">
      <span class="card-tag">IA & Tech</span>
    </div>
    <div class="card-content">
      <p class="card-date">25 de Junho, 2026</p>
      <h3 class="card-title">O Futuro dos Modelos de Linguagem na Programação</h3>
      <p class="card-excerpt">Entenda como as novas ferramentas de IA estão mudando a rotina dos desenvolvedores e o que esperar para os próximos anos.</p>
      <a href="#" class="card-link">Ler mais →</a>
    </div>
  </article>

  <article class="tech-card">
    <div class="card-image">
      <img src="https://via.placeholder.com/400x250" alt="Hardware e Gadgets">
      <span class="card-tag">Hardware</span>
    </div>
    <div class="card-content">
      <p class="card-date">22 de Junho, 2026</p>
      <h3 class="card-title">Review: Vale a pena investir em Processadores Quânticos domésticos?</h3>
      <p class="card-excerpt">Analisamos os novos processadores focados em entusiastas e se o custo-benefício realmente se justifica hoje.</p>
      <a href="#" class="card-link">Ler mais →</a>
    </div>
  </article>

</div>
/* Container que alinha os cards lado a lado e os torna responsivos */
.tech-card-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 24px;
  padding: 20px;
  font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}

/* Estilo individual de cada card */
.tech-card {
  background-color: #1e1e24; /* Fundo escuro estilo tech, mude para #ffffff se seu blog for claro */
  color: #ffffff;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  display: flex;
  flex-direction: column;
}

/* Efeito ao passar o mouse */
.tech-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 24px rgba(0, 123, 255, 0.25); /* Sombra neon azul */
}

/* Área da imagem */
.card-image {
  position: relative;
  width: 100%;
  height: 200px;
  overflow: hidden;
}

.card-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

/* Tag flutuante sobre a imagem */
.card-tag {
  position: absolute;
  top: 12px;
  left: 12px;
  background-color: #007bff; /* Azul Tech */
  color: #fff;
  padding: 4px 12px;
  font-size: 0.75rem;
  font-weight: bold;
  border-radius: 20px;
  text-transform: uppercase;
}

/* Corpo do texto dentro do card */
.card-content {
  padding: 20px;
  display: flex;
  flex-direction: column;
  flex-grow: 1;
}

.card-date {
  font-size: 0.8rem;
  color: #a0a0a0;
  margin-bottom: 8px;
}

.card-title {
  font-size: 1.25rem;
  margin: 0 0 12px 0;
  line-height: 1.4;
  font-weight: 600;
}

.card-excerpt {
  font-size: 0.95rem;
  color: #d1d1d1;
  line-height: 1.6;
  margin-bottom: 20px;
  flex-grow: 1;
}

/* Botão/Link de ação */
.card-link {
  color: #007bff;
  text-decoration: none;
  font-weight: bold;
  font-size: 0.9rem;
  align-self: flex-start;
  transition: color 0.2s img;
}

.card-link:hover {
  color: #0056b3;
  text-decoration: underline;
}
