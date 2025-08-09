---
layout: default
title: IBPK Berlin - Ingenieurbüro
description: Kompetente Planung und Beratung für alle Bereiche der modernen Gebäudetechnik
---

<style>
:root {
    --primary-color: #1e3a8a;
    --secondary-color: #374151;
    --accent-color: #2563eb;
    --text-primary: #1f2937;
    --text-secondary: #6b7280;
    --bg-primary: #ffffff;
    --bg-secondary: #f8fafc;
    --border-color: #e5e7eb;
    --shadow-card: 0 4px 6px rgba(0, 0, 0, 0.1);
}

body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
    line-height: 1.6;
    color: var(--text-primary);
    background: var(--bg-primary);
    margin: 0;
    padding: 0;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}

header {
    background: var(--primary-color);
    color: white;
    padding: 2rem 0;
    text-align: center;
    margin-bottom: 3rem;
}

.hero h1 {
    font-size: 2.5rem;
    font-weight: 600;
    margin-bottom: 1rem;
    color: white;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
    opacity: 0.9;
}

.stats {
    display: flex;
    justify-content: center;
    gap: 3rem;
    margin-top: 2rem;
}

.stat {
    text-align: center;
    color: white;
}

.stat-number {
    font-size: 2rem;
    font-weight: 700;
    display: block;
}

.stat-label {
    font-size: 0.9rem;
    opacity: 0.8;
    text-transform: uppercase;
    letter-spacing: 1px;
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin: 2rem 0;
}

.service-card {
    background: white;
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 2rem;
    box-shadow: var(--shadow-card);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
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
    color: var(--text-primary);
    font-size: 1.1rem;
    font-weight: 600;
    margin-bottom: 1rem;
}

.service-card p {
    color: var(--text-secondary);
    margin: 0;
}

section {
    margin: 4rem 0;
}

.section-title {
    font-size: 2.2rem;
    font-weight: 600;
    margin-bottom: 1rem;
    color: var(--text-primary);
    text-align: center;
}

.section-subtitle {
    font-size: 1.1rem;
    color: var(--text-secondary);
    text-align: center;
    margin-bottom: 3rem;
    max-width: 700px;
    margin-left: auto;
    margin-right: auto;
}

.company-stats {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 2rem;
    margin: 3rem 0;
    text-align: center;
}

.company-stat {
    padding: 2rem;
    background: var(--bg-secondary);
    border-radius: 8px;
}

.company-stat .number {
    font-size: 2.5rem;
    font-weight: 700;
    color: var(--primary-color);
    display: block;
    margin-bottom: 0.5rem;
}

.company-stat .label {
    color: var(--text-secondary);
    font-size: 0.9rem;
    text-transform: uppercase;
    letter-spacing: 1px;
}

.contact-methods {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin: 3rem 0;
}

.contact-method {
    background: white;
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 2rem;
    box-shadow: var(--shadow-card);
    transition: transform 0.3s ease;
}

.contact-method:hover {
    transform: translateY(-3px);
    border-color: var(--primary-color);
}

.contact-method h4 {
    color: var(--text-primary);
    margin-bottom: 0.5rem;
    font-size: 1.1rem;
}

.contact-method p {
    color: var(--text-secondary);
    margin: 0;
}

.cta-buttons {
    display: flex;
    gap: 1rem;
    justify-content: center;
    margin: 2rem 0;
}

.btn-primary {
    background: var(--primary-color);
    color: white;
    padding: 1rem 2rem;
    border: none;
    border-radius: 8px;
    text-decoration: none;
    font-weight: 600;
    transition: transform 0.3s ease;
}

.btn-primary:hover {
    transform: translateY(-2px);
    text-decoration: none;
    color: white;
}

.btn-secondary {
    background: transparent;
    color: var(--primary-color);
    padding: 1rem 2rem;
    border: 2px solid var(--primary-color);
    border-radius: 8px;
    text-decoration: none;
    font-weight: 600;
    transition: all 0.3s ease;
}

.btn-secondary:hover {
    background: var(--primary-color);
    color: white;
    text-decoration: none;
}

@media (max-width: 768px) {
    .stats {
        flex-direction: column;
        gap: 1.5rem;
    }
    
    .cta-buttons {
        flex-direction: column;
        align-items: center;
    }
    
    .services-grid,
    .contact-methods,
    .company-stats {
        grid-template-columns: 1fr;
    }
    
    .hero h1 {
        font-size: 2rem;
    }
    
    .section-title {
        font-size: 1.8rem;
    }
}
</style>

<header class="hero">
  <div class="container">
    <h1>Ingenieurbüro für technische Gebäudeausrüstung</h1>
    <p>Kompetente Planung und Beratung für alle Bereiche der modernen Gebäudetechnik.<br>Über 15 Jahre Erfahrung in der professionellen Umsetzung komplexer TGA-Projekte.</p>
    
    <div class="cta-buttons">
      <a href="#leistungen" class="btn-primary">Unsere Leistungen</a>
      <a href="#kontakt" class="btn-secondary">Beratungstermin</a>
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
</header>

<div class="container">

## <a name="leistungen"></a>Unsere Expertise

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

## <a name="unternehmen"></a>Innovation trifft Erfahrung

Mit über 15 Jahren Expertise in der technischen Gebäudeausrüstung realisieren wir zukunftsweisende Projekte. Unser interdisziplinäres Team vereint traditionelle Ingenieurskompetenz mit modernster Digitaltechnik.

<div class="company-stats">
  <div class="company-stat">
    <span class="number">500+</span>
    <span class="label">Projekte</span>
  </div>
  <div class="company-stat">
    <span class="number">15+</span>
    <span class="label">Jahre</span>
  </div>
  <div class="company-stat">
    <span class="number">50+</span>
    <span class="label">Kunden</span>
  </div>
</div>

## Referenz Projekte

**Smart Office Complex**  
Vollautomatisiertes Bürogebäude mit integrierter IoT-Steuerung

**Nachhaltiges Wohnen**  
Energieautarke Wohnanlage mit Wärmepumpen und PV-Anlage

**Industriekomplex**  
Hochverfügbare Elektroinstallation für Produktionsanlagen

## Karriere

Werde Teil eines innovativen Teams und arbeite an wegweisenden Projekten der Gebäudetechnik.

- ✓ **Innovation** - Modernste Technologien
- ✓ **Teamwork** - Interdisziplinäre Zusammenarbeit  
- ✓ **Entwicklung** - Kontinuierliche Weiterbildung
- ✓ **Work-Life** - Flexible Arbeitszeiten

<div style="text-align: center; margin: 2rem 0;">
  <a href="#kontakt" class="btn-primary">Jetzt bewerben</a>
</div>

## <a name="kontakt"></a>Lass uns sprechen

Bereit für Ihr nächstes Projekt? Kontaktieren Sie uns für eine kostenlose Beratung.

<div class="contact-methods">
  <div class="contact-method">
    <h4>E-Mail</h4>
    <p>info@technik-engineering.de</p>
  </div>
  
  <div class="contact-method">
    <h4>Telefon</h4>
    <p>+49 (0)30 12345678</p>
  </div>
  
  <div class="contact-method">
    <h4>Adresse</h4>
    <p>Musterstraße 123<br>10115 Berlin</p>
  </div>
</div>

---

<div style="text-align: center; color: var(--text-secondary); font-size: 0.9rem; margin: 3rem 0 1rem 0;">
  © 2024 Ingenieurbüro für die Planung von technischer Gebäudeausrüstung. Alle Rechte vorbehalten.
</div>

</div>
