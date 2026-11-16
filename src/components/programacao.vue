<template>
  <section class="coin-prog">
    <div class="prog-header">
      <span class="prog-badge">📅 Cronograma Oficial</span>
      <h2>Programação do Evento (22 a 25 de Maio)</h2>
    </div>

    <div class="days-grid">
      <div class="day-card">
        <div class="day-head">
          <span class="day-tag">Dia 01</span>
          <h3>22 de Maio de 2024</h3>
        </div>
        <ul class="schedule-list">
          <li><strong>08h00</strong> Pré-congresso, Oficinas, Minicursos, Workshops e Exposições</li>
          <li><strong>14h00</strong> Credenciamento Oficial — Escola de Governo</li>
          <li><strong>16h00</strong> Solenidade de Abertura (UERN, Governo do RN, FIOCRUZ e PAX)</li>
          <li><strong>16h30</strong> Mesa de Abertura: Sociedade e participação social na democracia</li>
          <li><strong>18h00</strong> Apresentação Cultural & Coquetel de Boas-vindas</li>
        </ul>
      </div>

      <div class="day-card">
        <div class="day-head">
          <span class="day-tag">Dia 02</span>
          <h3>23 de Maio de 2024</h3>
        </div>
        <ul class="schedule-list">
          <li><strong>08h00</strong> Oficinas, Minicursos e Espaços Audiovisuais</li>
          <li><strong>10h00</strong> Mesa Temática 1 — Tecnologias na Educação (UERN, UFERSA, UFRN)</li>
          <li><strong>14h30</strong> Palestra: O Impacto da IA na Transformação da Rede de Energia Elétrica</li>
          <li><strong>14h30</strong> Mesa Temática 2 — Turismo Verde (SETUR, IDEMA, UERN)</li>
          <li><strong>16h30</strong> Sessões de Comunicações Orais e Painéis Científicos</li>
        </ul>
      </div>

      <div class="day-card">
        <div class="day-head">
          <span class="day-tag">Dia 03</span>
          <h3>24 de Maio de 2024</h3>
        </div>
        <ul class="schedule-list">
          <li><strong>08h00</strong> Oficinas, Workshops e Mostras Científicas</li>
          <li><strong>10h00</strong> Mesa Temática 3 — Políticas Públicas em Saúde (UERN, FIOCRUZ)</li>
          <li><strong>14h30</strong> Palestra Especial: Geoparque Mundial da UNESCO — Geoparque Seridó</li>
          <li><strong>14h30</strong> Mesa Temática 4 — Educação e Formação de Professores</li>
          <li><strong>16h30</strong> Comunicações Orais e Grupos de Trabalho</li>
        </ul>
      </div>

      <div class="day-card">
        <div class="day-head">
          <span class="day-tag">Dia 04</span>
          <h3>25 de Maio de 2024</h3>
        </div>
        <ul class="schedule-list">
          <li><strong>08h00</strong> Atividades Práticas, Exposições e Mostra Audiovisual</li>
          <li><strong>10h00</strong> Mesa Temática 5 — Sustentabilidade, Clima e Transição Energética (UnB, UFRN, UFCG, UFC)</li>
          <li><strong>12h00</strong> Conferência e Mesa de Encerramento (Campus Natal & Plandites/UERN)</li>
        </ul>
      </div>
    </div>
  </section>
</template>

<style scoped>
.coin-prog {
  max-width: 1200px;
  margin: 2.5rem auto;
  padding: 0 1.5rem;
  font-family: 'Inter', 'Segoe UI', sans-serif;
}

.prog-header {
  text-align: center;
  margin-bottom: 1.75rem;
}

.prog-badge {
  display: inline-block;
  background: #dcfce7;
  color: #15803d;
  font-weight: 700;
  font-size: 0.78rem;
  padding: 0.3rem 0.9rem;
  border-radius: 999px;
  text-transform: uppercase;
  margin-bottom: 0.5rem;
}

.prog-header h2 {
  font-size: 1.75rem;
  font-weight: 800;
  color: #0f172a;
  margin: 0;
}

.days-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1.25rem;
}

.day-card {
  background: #ffffff;
  border: 1px solid #e2e8f0;
  border-radius: 20px;
  padding: 1.5rem;
  box-shadow: 0 8px 24px rgba(15, 23, 42, 0.04);
}

.day-head {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 1rem;
  padding-bottom: 0.75rem;
  border-bottom: 1px solid #f1f5f9;
}

.day-tag {
  background: #0284c7;
  color: #ffffff;
  font-weight: 700;
  font-size: 0.75rem;
  padding: 0.25rem 0.7rem;
  border-radius: 8px;
}

.day-head h3 {
  font-size: 1.1rem;
  font-weight: 800;
  color: #0f172a;
  margin: 0;
}

.schedule-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
  gap: 0.65rem;
}

.schedule-list li {
  font-size: 0.88rem;
  color: #334155;
  line-height: 1.45;
  display: flex;
  gap: 0.6rem;
}

.schedule-list li strong {
  color: #0284c7;
  min-width: 48px;
}
</style>
