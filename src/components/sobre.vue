<template>
  <section class="coin-sobre">
    <div class="sobre-card">
      <span class="coin-eyebrow">🎓 Congresso Interdisciplinar • UERN Campus Natal</span>
      <h1>Sociedade e Participação Social em Tempos de Reestruturação</h1>
      <p class="coin-subtitle">
        Sustentabilidade, Turismo, Saúde, Educação e Tecnologia • 22 a 25 de Maio de 2024
      </p>
      <p class="coin-lead">
        O Colóquio e Congresso Interdisciplinar representa um esforço conjunto em realizar ações, debates, exposições e trocas de saberes envolvendo ensino, pesquisa e extensão na UERN (Campus Avançado de Natal), com foco na inclusão social e no diálogo com as Políticas Públicas junto ao GT Geoparques Mundiais UNESCO.
      </p>

      <div class="eixos-grid">
        <div class="eixo-item">
          <span class="eixo-num">Eixo 01</span>
          <h4>Geoparques & Sustentabilidade</h4>
          <p>Estilo de vida, bem-estar, territórios saudáveis e envolvimento com a natureza.</p>
        </div>
        <div class="eixo-item">
          <span class="eixo-num">Eixo 02</span>
          <h4>Turismo & Cultura</h4>
          <p>Apropriação histórica, cultural e econômica em suas variadas vertentes regionais.</p>
        </div>
        <div class="eixo-item">
          <span class="eixo-num">Eixo 03</span>
          <h4>Políticas Públicas em Saúde</h4>
          <p>Promoção da saúde coletiva, equidade e articulação interinstitucional.</p>
        </div>
        <div class="eixo-item">
          <span class="eixo-num">Eixo 04</span>
          <h4>Educação Docente</h4>
          <p>Práticas pedagógicas inclusivas e formação de professores contemporânea.</p>
        </div>
        <div class="eixo-item">
          <span class="eixo-num">Eixo 05</span>
          <h4>Tecnologia & Democracia</h4>
          <p>Tecnologia informacional, movimentos sociais, IA e participação cidadã.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.coin-sobre {
  max-width: 1200px;
  margin: 2rem auto;
  padding: 0 1.5rem;
  font-family: 'Inter', 'Segoe UI', sans-serif;
}

.sobre-card {
  background: #ffffff;
  border-radius: 24px;
  padding: 2.5rem;
  border: 1px solid #e2e8f0;
  box-shadow: 0 14px 35px rgba(15, 23, 42, 0.06);
}

.coin-eyebrow {
  display: inline-block;
  background: #e0f2fe;
  color: #0369a1;
  font-weight: 700;
  font-size: 0.78rem;
  padding: 0.35rem 0.95rem;
  border-radius: 999px;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  margin-bottom: 0.85rem;
}

h1 {
  font-size: 2rem;
  font-weight: 800;
  color: #0f172a;
  margin: 0 0 0.5rem 0;
  line-height: 1.25;
}

.coin-subtitle {
  font-size: 1.1rem;
  font-weight: 600;
  color: #0284c7;
  margin: 0 0 1.25rem 0;
}

.coin-lead {
  font-size: 0.98rem;
  color: #475569;
  line-height: 1.7;
  margin: 0 0 2rem 0;
}

.eixos-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
}

.eixo-item {
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 16px;
  padding: 1.25rem;
}

.eixo-num {
  display: inline-block;
  font-size: 0.72rem;
  font-weight: 800;
  text-transform: uppercase;
  color: #0284c7;
  background: #e0f2fe;
  padding: 3px 9px;
  border-radius: 999px;
  margin-bottom: 0.5rem;
}

.eixo-item h4 {
  font-size: 0.96rem;
  font-weight: 700;
  color: #1e293b;
  margin: 0 0 0.4rem 0;
}

.eixo-item p {
  font-size: 0.84rem;
  color: #64748b;
  line-height: 1.5;
  margin: 0;
}
</style>
