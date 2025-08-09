---
layout: default
title: IBPK Berlin - Ingenieurbüro
description: Kompetente Planung und Beratung für alle Bereiche der modernen Gebäudetechnik
---

<style>
:root {
  --primary-color: #1e3a8a;
  --text-primary: #1f2937;
  --text-secondary: #6b7280;
  --bg-primary: #ffffff;
  --bg-secondary: #f8fafc;
  --border-color: #e5e7eb;
  --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif;
  line-height: 1.6;
  color: var(--text-primary);
  margin: 0;
}

.hero {
  background: var(--primary-color);
  color: white;
  padding: 4rem 2rem;
  text-align: center;
}

.hero h1 {
  font-size: 2.5rem;
  font-weight: 600;
  margin-bottom: 1rem;
}

.hero-subtitle {
  font-size: 1.2rem;
  margin-bottom: 2rem;
  opacity: 0.9;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

.stats {
  display: flex;
  justify-content: center;
  gap: 3rem;
  margin-top: 2rem;
  flex-wrap: wrap;
}

.stat {
  text-align: center;
}

.stat-number {
  font-size: 2rem;
  font-weight: 700;
  display: block;
}

.stat-label {
  font-size: 0.9rem;
  opacity: 0.8;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

.section {
  margin: 4rem 0;
}

.section-title {
  font-size: 2.2rem;
  font-weight: 600;
  margin-bottom: 1rem;
  text-align: center;
}

.section-subtitle {
  font-size: 1.1rem;
  color: var(--text-secondary);
  text-align: center;
  margin-bottom: 3rem;
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 3rem 0;
}

.service-card {
  background: white;
  border: 1px solid var(--border-color);
  border-radius: 8px;
  padding: 2rem;
  box-shadow: var(--shadow);
  transition: all 0.3s ease;
}

.service-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
}

.service-card.featured {
  border-color: var(--primary-color);
  background: linear-gradient(135deg, white 0%, rgba(30, 58, 138, 0.05) 100%);
}

.service-card h3 {
  font-size: 1.1rem;
  margin-bottom: 1rem;
  color: var(--text-primary);
}

.service-card p {
  color: var(--text-secondary);
  margin: 0;
}

.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin: 3rem 0;
}

.contact-card {
  background: white;
  border: 1px solid var(--border-color);
  border-radius: 8px;
  padding: 2rem;
  box-shadow: var(--shadow);
  transition: all 0.3s ease;
}

.contact-card:hover {
  transform: translateY(-3px);
  border-color: var(--primary-color);
}

.contact-card h4 {
  margin-bottom: 0.5rem;
  color: var(--text-primary);
}

.contact-card p {
  margin: 0;
  color: var(--text-secondary);
}

.btn {
  display: inline-block;
  padding: 1rem 2rem;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
  margin: 0.5rem;
}

.btn-primary {
  background: var(--primary-color);
  color: white;
}

.btn-primary:hover {
  transform: translateY(-2px);
  color: white;
  text-decoration: none;
}

.btn-secondary {
  background: transparent;
  color: var(--primary-color);
  border: 2px solid var(--primary-color);
}

.btn-secondary:hover {
  background: var(--primary-color);
  color: white;
  text-decoration: none;
}

.text-center {
  text-align: center;
}

@media (max-width: 768px) {
  .hero h1 { font-size: 2rem; }
  .stats { flex-direction: column; gap: 1.5rem; }
  .services-grid, .contact-grid { grid-template-columns: 1fr; }
}
</style>

<div class="hero">
  <h1>Ingenieurbüro für technische Gebäudeausrüstung</h1>
  <div class="hero-subtitle">
    Kompetente Planung und Beratung für alle Bereiche der modernen Gebäudetechnik.<br>
    Über 15 Jahre Erfahrung in der professionellen Umsetzung komplexer TGA-Projekte.
  </div>
  
  <div class="stats">
    <div class="stat">
      <span class="stat-number">500+</span>
      <span class="stat-label">Projekte</span>
    </div>
    <div class="stat">
      <span class="stat-number">15+</span>
      <span class="stat-label">Jahre Erfahrung</span>
    </div>
    <div class="stat">
      <span class="stat-number">50+</span>
      <span class="stat-label">Zufriedene Kunden</span>
    </div>
  </div>
</div>

<div class="container">

<div class="section">
  <h2 class="section-title">Unsere Expertise</h2>
  <p class="section-subtitle">Komplettlösungen für moderne Gebäudetechnik</p>

  <div class="services-grid">
    <div class="service-card">
      <h3>KG 400 - Technische Anlagen</h3>
      <p>Gesamtplanung und Koordination aller technischen Systeme</p>
    </div>
    
    <div class="service-card">
      <h3>KG 410 - Wasser & Gas</h3>
      <p>Sanitärtechnik und Versorgungsinstallationen</p>
    </div>
    
    <div class="service-card">
      <h3>KG 420 - Wärmeversorgung</h3>
      <p>Heizung, Wärmepumpen und Energiesysteme</p>
    </div>
    
    <div class="service-card">
      <h3>KG 430 - Klimatechnik</h3>
      <p>Lüftung, Klimatisierung und Luftqualität</p>
    </div>
    
    <div class="service-card featured">
      <h3>KG 440 - Elektrotechnik</h3>
      <p>Starkstrom, Verteilung und E-Mobility</p>
    </div>
    
    <div class="service-card featured">
      <h3>KG 450 - IT & Telekom</h3>
      <p>Smart Building und Digitalisierung</p>
    </div>
    
    <div class="service-card">
      <h3>KG 460 - Förderanlagen</h3>
      <p>Aufzüge und Transportsysteme</p>
    </div>
    
    <div class="service-card">
      <h3>KG 470 - Spezialanlagen</h3>
      <p>Individuelle technische Lösungen</p>
    </div>
    
    <div class="service-card">
      <h3>KG 480 - Automation</h3>
      <p>Intelligente Gebäudesteuerung</p>
    </div>
  </div>
</div>

<div class="section">
  <h2 class="section-title">Innovation trifft Erfahrung</h2>
  <p>Mit über 15 Jahren Expertise in der technischen Gebäudeausrüstung realisieren wir zukunftsweisende Projekte. Unser interdisziplinäres Team vereint traditionelle Ingenieurskompetenz mit modernster Digitaltechnik.</p>
</div>

<div class="section">
  <h2 class="section-title">Referenz Projekte</h2>
  
  <div class="services-grid">
    <div class="service-card">
      <h3>Smart Office Complex</h3>
      <p>Vollautomatisiertes Bürogebäude mit integrierter IoT-Steuerung</p>
    </div>
    
    <div class="service-card">
      <h3>Nachhaltiges Wohnen</h3>
      <p>Energieautarke Wohnanlage mit Wärmepumpen und PV-Anlage</p>
    </div>
    
    <div class="service-card">
      <h3>Industriekomplex</h3>
      <p>Hochverfügbare Elektroinstallation für Produktionsanlagen</p>
    </div>
  </div>
</div>

<div class="section">
  <h2 class="section-title">Karriere</h2>
  <p class="text-center">Werde Teil eines innovativen Teams und arbeite an wegweisenden Projekten der Gebäudetechnik.</p>
  
  <ul style="max-width: 600px; margin: 2rem auto;">
    <li><strong>Innovation</strong> - Modernste Technologien</li>
    <li><strong>Teamwork</strong> - Interdisziplinäre Zusammenarbeit</li>
    <li><strong>Entwicklung</strong> - Kontinuierliche Weiterbildung</li>
    <li><strong>Work-Life</strong> - Flexible Arbeitszeiten</li>
  </ul>
</div>

<div class="section">
  <h2 class="section-title">Kontakt</h2>
  <p class="section-subtitle">Bereit für Ihr nächstes Projekt? Kontaktieren Sie uns für eine kostenlose Beratung.</p>
  
  <div class="contact-grid">
    <div class="contact-card">
      <h4>E-Mail</h4>
      <p>info@technik-engineering.de</p>
    </div>
    
    <div class="contact-card">
      <h4>Telefon</h4>
      <p>+49 (0)30 12345678</p>
    </div>
    
    <div class="contact-card">
      <h4>Adresse</h4>
      <p>Musterstraße 123<br>10115 Berlin</p>
    </div>
  </div>
  
  <div class="text-center">
    <a href="mailto:info@technik-engineering.de" class="btn btn-primary">Beratungstermin</a>
    <a href="tel:+4903012345678" class="btn btn-secondary">Anrufen</a>
  </div>
</div>

</div>

---

<div style="text-align: center; color: #6b7280; font-size: 0.9rem; padding: 2rem;">
  © 2024 Ingenieurbüro für die Planung von technischer Gebäudeausrüstung. Alle Rechte vorbehalten.
</div>
