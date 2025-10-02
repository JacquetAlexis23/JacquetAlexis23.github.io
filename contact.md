---
layout: default
title: "Contacto"
permalink: /contact/
---

<div class="contact-hero">
  <div class="container">
    <h1>Conecta Conmigo</h1>
    <p class="lead">
      ¿Tienes un proyecto de Data Science en mente? ¿Necesitas consultoría en Machine Learning? 
      ¿O simplemente quieres discutir sobre IA y tecnología? 
      <br><strong>¡Me encantaría escucharte!</strong>
    </p>
  </div>
</div>

<div class="contact-content">
  <div class="container">
    <div class="contact-grid">
      
      <!-- Información de Contacto -->
      <div class="contact-info">
        <h2>Información de Contacto</h2>
        
        <div class="contact-methods">
          <div class="contact-method">
            <div class="contact-icon">
              <i class="fas fa-envelope"></i>
            </div>
            <div class="contact-details">
              <h3>Email</h3>
              <p>tu-email@gmail.com</p>
              <small>Respuesta garantizada en 24 horas</small>
            </div>
          </div>
          
          <div class="contact-method">
            <div class="contact-icon">
              <i class="fab fa-linkedin"></i>
            </div>
            <div class="contact-details">
              <h3>LinkedIn</h3>
              <p><a href="https://linkedin.com/in/tu-perfil" target="_blank">linkedin.com/in/tu-perfil</a></p>
              <small>Conectemos profesionalmente</small>
            </div>
          </div>
          
          <div class="contact-method">
            <div class="contact-icon">
              <i class="fab fa-github"></i>
            </div>
            <div class="contact-details">
              <h3>GitHub</h3>
              <p><a href="https://github.com/TuUsuario" target="_blank">github.com/TuUsuario</a></p>
              <small>Explora mi código y proyectos</small>
            </div>
          </div>
          
          <div class="contact-method">
            <div class="contact-icon">
              <i class="fas fa-map-marker-alt"></i>
            </div>
            <div class="contact-details">
              <h3>Ubicación</h3>
              <p>Tu Ciudad, Tu País</p>
              <small>Disponible para proyectos remotos</small>
            </div>
          </div>
        </div>
        
        <div class="availability">
          <h3>🕒 Disponibilidad</h3>
          <div class="availability-grid">
            <div class="availability-item">
              <span class="status available"></span>
              <span>Proyectos de Consultoría</span>
            </div>
            <div class="availability-item">
              <span class="status available"></span>
              <span>Colaboraciones Open Source</span>
            </div>
            <div class="availability-item">
              <span class="status available"></span>
              <span>Oportunidades Laborales</span>
            </div>
            <div class="availability-item">
              <span class="status limited"></span>
              <span>Proyectos Freelance (Limitado)</span>
            </div>
          </div>
        </div>
      </div>
      
      <!-- Formulario de Contacto -->
      <div class="contact-form-section">
        <h2>Envíame un Mensaje</h2>
        
        <form class="contact-form" id="contactForm">
          <div class="form-group">
            <label for="name">Nombre *</label>
            <input type="text" id="name" name="name" required>
          </div>
          
          <div class="form-group">
            <label for="email">Email *</label>
            <input type="email" id="email" name="email" required>
          </div>
          
          <div class="form-group">
            <label for="company">Empresa / Organización</label>
            <input type="text" id="company" name="company">
          </div>
          
          <div class="form-group">
            <label for="subject">Tipo de Proyecto *</label>
            <select id="subject" name="subject" required>
              <option value="">Selecciona una opción</option>
              <option value="consultation">Consultoría en Data Science</option>
              <option value="ml-project">Proyecto de Machine Learning</option>
              <option value="analytics">Business Analytics</option>
              <option value="collaboration">Colaboración / Partnership</option>
              <option value="job-opportunity">Oportunidad Laboral</option>
              <option value="other">Otro</option>
            </select>
          </div>
          
          <div class="form-group">
            <label for="budget">Presupuesto Estimado</label>
            <select id="budget" name="budget">
              <option value="">Selecciona un rango</option>
              <option value="under-5k">Menos de $5,000</option>
              <option value="5k-15k">$5,000 - $15,000</option>
              <option value="15k-50k">$15,000 - $50,000</option>
              <option value="50k-plus">Más de $50,000</option>
              <option value="negotiable">A negociar</option>
            </select>
          </div>
          
          <div class="form-group">
            <label for="timeline">Timeline del Proyecto</label>
            <select id="timeline" name="timeline">
              <option value="">Selecciona un timeline</option>
              <option value="asap">Lo antes posible</option>
              <option value="1-month">1 mes</option>
              <option value="2-3-months">2-3 meses</option>
              <option value="3-6-months">3-6 meses</option>
              <option value="6-plus-months">Más de 6 meses</option>
              <option value="flexible">Flexible</option>
            </select>
          </div>
          
          <div class="form-group">
            <label for="message">Descripción del Proyecto *</label>
            <textarea id="message" name="message" rows="6" required 
                      placeholder="Describe tu proyecto, objetivos, datos disponibles, y cualquier información relevante que me ayude a entender mejor tus necesidades."></textarea>
          </div>
          
          <div class="form-group">
            <label class="checkbox-label">
              <input type="checkbox" id="newsletter" name="newsletter">
              <span class="checkmark"></span>
              Quiero recibir actualizaciones sobre nuevos artículos y proyectos
            </label>
          </div>
          
          <button type="submit" class="btn btn-primary submit-btn">
            <i class="fas fa-paper-plane"></i>
            Enviar Mensaje
          </button>
        </form>
      </div>
      
    </div>
  </div>
</div>

<div class="services-section">
  <div class="container">
    <h2>¿En qué puedo ayudarte?</h2>
    
    <div class="services-grid">
      <div class="service-card">
        <div class="service-icon">
          <i class="fas fa-brain"></i>
        </div>
        <h3>Machine Learning Consulting</h3>
        <p>
          Desarrollo de modelos predictivos, sistemas de recomendación, 
          y soluciones de ML end-to-end adaptadas a tu negocio.
        </p>
        <ul>
          <li>Análisis de viabilidad técnica</li>
          <li>Arquitectura de soluciones ML</li>
          <li>Implementación y deployment</li>
          <li>Optimización de performance</li>
        </ul>
      </div>
      
      <div class="service-card">
        <div class="service-icon">
          <i class="fas fa-chart-line"></i>
        </div>
        <h3>Business Analytics</h3>
        <p>
          Transformo tus datos en insights accionables que impulsen 
          decisiones estratégicas y generen valor empresarial medible.
        </p>
        <ul>
          <li>Análisis exploratorio de datos</li>
          <li>Dashboards interactivos</li>
          <li>KPIs y métricas de negocio</li>
          <li>Reportes ejecutivos</li>
        </ul>
      </div>
      
      <div class="service-card">
        <div class="service-icon">
          <i class="fas fa-eye"></i>
        </div>
        <h3>Computer Vision</h3>
        <p>
          Soluciones de visión artificial para automatización de procesos, 
          control de calidad, y análisis de imágenes en tiempo real.
        </p>
        <ul>
          <li>Detección y clasificación de objetos</li>
          <li>Control de calidad automatizado</li>
          <li>Análisis de imágenes médicas</li>
          <li>Sistemas de vigilancia inteligente</li>
        </ul>
      </div>
      
      <div class="service-card">
        <div class="service-icon">
          <i class="fas fa-comments"></i>
        </div>
        <h3>Natural Language Processing</h3>
        <p>
          Procesamiento de texto avanzado para análisis de sentimientos, 
          chatbots, traducción automática y extracción de información.
        </p>
        <ul>
          <li>Análisis de sentimientos</li>
          <li>Chatbots y asistentes virtuales</li>
          <li>Traducción automática</li>
          <li>Clasificación de documentos</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<div class="testimonials-section">
  <div class="container">
    <h2>Lo que dicen mis colaboradores</h2>
    
    <div class="testimonials-grid">
      <div class="testimonial-card">
        <div class="testimonial-content">
          <p>
            "Excelente trabajo en nuestro proyecto de análisis de sentimientos. 
            La solución implementada superó nuestras expectativas en precisión 
            y velocidad de procesamiento."
          </p>
        </div>
        <div class="testimonial-author">
          <img src="/assets/testimonials/client1.jpg" alt="Cliente 1">
          <div class="author-info">
            <h4>Ana García</h4>
            <span>CTO, TechCorp</span>
          </div>
        </div>
      </div>
      
      <div class="testimonial-card">
        <div class="testimonial-content">
          <p>
            "Su enfoque en generar valor de negocio real, no solo métricas técnicas, 
            fue clave para el éxito de nuestro proyecto de segmentación de clientes. 
            ROI del 300% en el primer año."
          </p>
        </div>
        <div class="testimonial-author">
          <img src="/assets/testimonials/client2.jpg" alt="Cliente 2">
          <div class="author-info">
            <h4>Carlos Mendoza</h4>
            <span>Director de Marketing, RetailPlus</span>
          </div>
        </div>
      </div>
      
      <div class="testimonial-card">
        <div class="testimonial-content">
          <p>
            "Profesional, puntual y con gran capacidad para explicar conceptos 
            complejos de manera clara. Definitivamente recomendaría sus servicios 
            para cualquier proyecto de ML."
          </p>
        </div>
        <div class="testimonial-author">
          <img src="/assets/testimonials/client3.jpg" alt="Cliente 3">
          <div class="author-info">
            <h4>María López</h4>
            <span>VP of Operations, InnovateLab</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="response-time">
  <div class="container">
    <div class="response-card">
      <h3>⚡ Tiempo de Respuesta Garantizado</h3>
      <p>
        Me comprometo a responder todos los mensajes dentro de <strong>24 horas</strong>. 
        Para proyectos urgentes, contáctame directamente por LinkedIn.
      </p>
      <div class="response-stats">
        <div class="stat">
          <span class="stat-number">< 4h</span>
          <span class="stat-label">Respuesta Promedio</span>
        </div>
        <div class="stat">
          <span class="stat-number">98%</span>
          <span class="stat-label">Satisfacción Cliente</span>
        </div>
        <div class="stat">
          <span class="stat-number">50+</span>
          <span class="stat-label">Proyectos Completados</span>
        </div>
      </div>
    </div>
  </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
    const form = document.getElementById('contactForm');
    
    form.addEventListener('submit', function(e) {
        e.preventDefault();
        
        // Simular envío del formulario
        const submitBtn = form.querySelector('.submit-btn');
        const originalText = submitBtn.innerHTML;
        
        submitBtn.innerHTML = '<i class="fas fa-spinner fa-spin"></i> Enviando...';
        submitBtn.disabled = true;
        
        setTimeout(function() {
            submitBtn.innerHTML = '<i class="fas fa-check"></i> ¡Mensaje Enviado!';
            submitBtn.classList.add('success');
            
            setTimeout(function() {
                submitBtn.innerHTML = originalText;
                submitBtn.disabled = false;
                submitBtn.classList.remove('success');
                form.reset();
                
                alert('¡Gracias por tu mensaje! Te responderé dentro de 24 horas.');
            }, 2000);
        }, 1500);
    });
});
</script>