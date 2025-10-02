---
layout: default
title: "Proyectos"
permalink: /projects/
---

<div class="projects-hero">
  <div class="container">
    <h1>Portfolio de Proyectos</h1>
    <p class="lead">
      Soluciones de Machine Learning y Data Science que transforman datos en valor empresarial.
      Cada proyecto incluye análisis de ROI, métricas de rendimiento y código production-ready.
    </p>
  </div>
</div>

<div class="projects-filter">
  <div class="container">
    <div class="filter-buttons">
      <button class="filter-btn active" data-filter="all">Todos</button>
      <button class="filter-btn" data-filter="deep-learning">Deep Learning</button>
      <button class="filter-btn" data-filter="machine-learning">Machine Learning</button>
      <button class="filter-btn" data-filter="nlp">NLP</button>
      <button class="filter-btn" data-filter="computer-vision">Computer Vision</button>
      <button class="filter-btn" data-filter="business-analytics">Business Analytics</button>
    </div>
  </div>
</div>

<div class="projects-grid">
  <div class="container">
    
    <!-- Proyecto 1: Análisis de Sentimientos -->
    <div class="project-card featured" data-categories="deep-learning nlp" id="sentiment-analysis">
      <div class="project-image">
        <img src="/assets/projects/sentiment-analysis.jpg" alt="Análisis de Sentimientos Twitter">
        <div class="project-overlay">
          <div class="project-badges">
            <span class="badge badge-featured">🔥 Proyecto Estrella</span>
            <span class="badge badge-tech">Deep Learning</span>
            <span class="badge badge-tech">NLP</span>
          </div>
        </div>
      </div>
      
      <div class="project-content">
        <h3>🧠 Twitter Sentiment Analysis con Deep CNN</h3>
        <p class="project-description">
          Red neuronal convolucional profunda para análisis de sentimientos en tiempo real. 
          Procesa 1.6M+ tweets con más del 85% de precisión, ideal para monitoreo de marca 
          y detección temprana de crisis.
        </p>
        
        <div class="project-stats">
          <div class="stat">
            <span class="stat-value">1.6M+</span>
            <span class="stat-label">Tweets Procesados</span>
          </div>
          <div class="stat">
            <span class="stat-value">85%+</span>
            <span class="stat-label">Precisión</span>
          </div>
          <div class="stat">
            <span class="stat-value">$500K+</span>
            <span class="stat-label">ROI Anual</span>
          </div>
        </div>
        
        <div class="project-tech">
          <span class="tech-tag">TensorFlow</span>
          <span class="tech-tag">CNN</span>
          <span class="tech-tag">NLP</span>
          <span class="tech-tag">Python</span>
        </div>
        
        <div class="project-actions">
          <a href="https://github.com/TuUsuario/sentiment-analysis" class="btn btn-primary" target="_blank">
            <i class="fab fa-github"></i> Ver Código
          </a>
          <a href="#" class="btn btn-secondary demo-btn">
            <i class="fas fa-play"></i> Demo Live
          </a>
        </div>
      </div>
    </div>
    
    <!-- Proyecto 2: Data Science para Negocios -->
    <div class="project-card" data-categories="machine-learning business-analytics" id="business-analytics">
      <div class="project-image">
        <img src="/assets/projects/business-analytics.jpg" alt="Data Science para Negocios">
        <div class="project-overlay">
          <div class="project-badges">
            <span class="badge badge-suite">Suite de 6 Proyectos</span>
            <span class="badge badge-tech">ML</span>
          </div>
        </div>
      </div>
      
      <div class="project-content">
        <h3>📊 Data Science Aplicado a Negocios</h3>
        <p class="project-description">
          Suite completa de 6 proyectos de Machine Learning aplicados a diferentes departamentos 
          empresariales: HR, Marketing, Ventas, Operaciones, PR y Mantenimiento.
        </p>
        
        <div class="project-departments">
          <div class="department">
            <h4>👥 Human Resources</h4>
            <p>Predicción de rotación de empleados (15-20% reducción de costos)</p>
          </div>
          <div class="department">
            <h4>📈 Marketing</h4>
            <p>Segmentación de clientes (25-30% mejora en conversión)</p>
          </div>
          <div class="department">
            <h4>💰 Sales</h4>
            <p>Forecasting de ventas (10-15% reducción de costos inventario)</p>
          </div>
          <div class="department">
            <h4>🏭 Operations</h4>
            <p>Computer Vision para control de calidad (90% reducción tiempo inspección)</p>
          </div>
          <div class="department">
            <h4>🗣️ Public Relations</h4>
            <p>Análisis de sentimientos (70% respuesta más rápida)</p>
          </div>
          <div class="department">
            <h4>🔧 Maintenance</h4>
            <p>Detección de defectos (80% reducción defectos no detectados)</p>
          </div>
        </div>
        
        <div class="project-tech">
          <span class="tech-tag">Scikit-learn</span>
          <span class="tech-tag">Computer Vision</span>
          <span class="tech-tag">Time Series</span>
          <span class="tech-tag">Clustering</span>
        </div>
        
        <div class="project-actions">
          <a href="https://github.com/TuUsuario/ds-business-applications" class="btn btn-primary" target="_blank">
            <i class="fab fa-github"></i> Ver Código
          </a>
          <a href="#" class="btn btn-secondary">
            <i class="fas fa-chart-bar"></i> Business Report
          </a>
        </div>
      </div>
    </div>
    
    <!-- Proyecto 3: Traductor Neural -->
    <div class="project-card" data-categories="deep-learning nlp" id="neural-translator">
      <div class="project-image">
        <img src="/assets/projects/translator.jpg" alt="Traductor Neural">
        <div class="project-overlay">
          <div class="project-badges">
            <span class="badge badge-advanced">Implementación desde Cero</span>
            <span class="badge badge-tech">Transformers</span>
          </div>
        </div>
      </div>
      
      <div class="project-content">
        <h3>🌐 Neural Machine Translation con Transformers</h3>
        <p class="project-description">
          Implementación completa desde cero de la arquitectura Transformer para traducción 
          automática inglés-español. Demuestra comprensión profunda de attention mechanisms 
          y procesamiento de secuencias.
        </p>
        
        <div class="project-features">
          <ul>
            <li>✅ Arquitectura Transformer implementada desde cero</li>
            <li>✅ Multi-head attention mechanism</li>
            <li>✅ Positional encoding personalizado</li>
            <li>✅ Dataset Europarl v7 (2M+ pares de oraciones)</li>
            <li>✅ Custom learning rate scheduling</li>
            <li>✅ Subword tokenization (BPE)</li>
          </ul>
        </div>
        
        <div class="project-metrics">
          <div class="metric">
            <span class="metric-label">Reducción de Costos:</span>
            <span class="metric-value">70% vs. traducción manual</span>
          </div>
          <div class="metric">
            <span class="metric-label">Velocidad:</span>
            <span class="metric-value">1000+ documentos/hora</span>
          </div>
          <div class="metric">
            <span class="metric-label">Calidad:</span>
            <span class="metric-value">Near-human quality</span>
          </div>
        </div>
        
        <div class="project-tech">
          <span class="tech-tag">TensorFlow</span>
          <span class="tech-tag">Transformer</span>
          <span class="tech-tag">Attention</span>
          <span class="tech-tag">NLP</span>
        </div>
        
        <div class="project-actions">
          <a href="https://github.com/TuUsuario/neural-translator" class="btn btn-primary" target="_blank">
            <i class="fab fa-github"></i> Ver Código
          </a>
          <a href="#" class="btn btn-secondary">
            <i class="fas fa-language"></i> Probar Traductor
          </a>
        </div>
      </div>
    </div>
    
    <!-- Proyecto 4: Análisis de Mercado Henry -->
    <div class="project-card" data-categories="business-analytics machine-learning" id="market-analysis">
      <div class="project-image">
        <img src="/assets/projects/market-analysis.jpg" alt="Análisis de Mercado">
        <div class="project-overlay">
          <div class="project-badges">
            <span class="badge badge-business">Business Intelligence</span>
            <span class="badge badge-tech">API Integration</span>
          </div>
        </div>
      </div>
      
      <div class="project-content">
        <h3>🔍 Análisis de Mercado Gastronómico - Proyecto Henry</h3>
        <p class="project-description">
          Análisis integral del mercado gastronómico utilizando datos de Yelp API. 
          Incluye análisis geoespacial, segmentación de mercado y recomendaciones 
          estratégicas basadas en datos.
        </p>
        
        <div class="project-highlights">
          <div class="highlight">
            <h4>🎯 Objetivo</h4>
            <p>Identificar oportunidades de mercado y ubicaciones óptimas para nuevos restaurantes</p>
          </div>
          <div class="highlight">
            <h4>📊 Metodología</h4>
            <p>EDA completo, análisis geoespacial, clustering de ubicaciones, análisis de competencia</p>
          </div>
          <div class="highlight">
            <h4>💼 Resultado</h4>
            <p>Recomendaciones estratégicas con potencial ROI de 15-25% en nuevas aperturas</p>
          </div>
        </div>
        
        <div class="project-tech">
          <span class="tech-tag">Pandas</span>
          <span class="tech-tag">API Integration</span>
          <span class="tech-tag">Geospatial Analysis</span>
          <span class="tech-tag">Visualization</span>
        </div>
        
        <div class="project-actions">
          <a href="https://github.com/TuUsuario/market-analysis-henry" class="btn btn-primary" target="_blank">
            <i class="fab fa-github"></i> Ver Código
          </a>
          <a href="#" class="btn btn-secondary">
            <i class="fas fa-file-pdf"></i> Reporte Ejecutivo
          </a>
        </div>
      </div>
    </div>
    
  </div>
</div>

<div class="additional-projects">
  <div class="container">
    <h2>Proyectos Adicionales</h2>
    <p class="text-center">Explora más proyectos y contribuciones en mi perfil de GitHub</p>
    
    <div class="github-stats">
      <div class="stat-card">
        <h3>⭐ Repositorios Destacados</h3>
        <p>Proyectos con mayor impacto y reutilización</p>
        <a href="https://github.com/TuUsuario?tab=repositories&sort=stargazers" class="btn btn-outline" target="_blank">
          Ver en GitHub
        </a>
      </div>
      
      <div class="stat-card">
        <h3>🔧 Contribuciones</h3>
        <p>Colaboraciones en proyectos open source</p>
        <a href="https://github.com/TuUsuario" class="btn btn-outline" target="_blank">
          Ver Actividad
        </a>
      </div>
      
      <div class="stat-card">
        <h3>📚 Recursos</h3>
        <p>Tutoriales y código educativo</p>
        <a href="https://github.com/TuUsuario?tab=repositories&type=source" class="btn btn-outline" target="_blank">
          Explorar
        </a>
      </div>
    </div>
  </div>
</div>

<div class="collaboration-cta">
  <div class="container">
    <h2>¿Tienes un proyecto en mente?</h2>
    <p>
      Estoy disponible para colaboraciones, consultoría y desarrollo de soluciones 
      personalizadas de Machine Learning y Data Science.
    </p>
    <div class="cta-buttons">
      <a href="/contact" class="btn btn-primary">Contactar</a>
      <a href="https://github.com/TuUsuario" class="btn btn-secondary" target="_blank">
        <i class="fab fa-github"></i> Ver GitHub
      </a>
    </div>
  </div>
</div>

<script>
// Filter functionality
document.addEventListener('DOMContentLoaded', function() {
    const filterButtons = document.querySelectorAll('.filter-btn');
    const projectCards = document.querySelectorAll('.project-card');
    
    filterButtons.forEach(button => {
        button.addEventListener('click', function() {
            const filter = this.getAttribute('data-filter');
            
            // Update active button
            filterButtons.forEach(btn => btn.classList.remove('active'));
            this.classList.add('active');
            
            // Filter projects
            projectCards.forEach(card => {
                if (filter === 'all') {
                    card.style.display = 'block';
                } else {
                    const categories = card.getAttribute('data-categories');
                    if (categories && categories.includes(filter)) {
                        card.style.display = 'block';
                    } else {
                        card.style.display = 'none';
                    }
                }
            });
        });
    });
});
</script>