
<!DOCTYPE html>
<html lang="en-ZA">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#102039">
<meta name="description" content="Discover South African legal education, candidate attorney resources, legal research and leading law firms.">
<title>Legal Learning Institute SA</title>

<style>
/* =================================
   LEGAL LEARNING INSTITUTE SA
   All styling is included in this file
================================= */

:root {
  --navy: #102039;
  --navy-light: #203653;
  --gold: #c9a76b;
  --cream: #f7f5f0;
  --white: #ffffff;
  --text: #263449;
  --muted: #6d7787;
  --border: #e5e1d8;
  --green: #35664e;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: 85px;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: var(--white);
  color: var(--text);
  line-height: 1.7;
}

a {
  color: inherit;
  text-decoration: none;
}

button, input, select {
  font: inherit;
}

button, a, input, select {
  -webkit-tap-highlight-color: transparent;
}

button:focus-visible,
a:focus-visible,
input:focus-visible,
select:focus-visible {
  outline: 3px solid var(--gold);
  outline-offset: 3px;
}

.container {
  width: min(1160px, 92%);
  margin: auto;
}

.eyebrow {
  color: var(--gold);
  font-size: 11px;
  font-weight: bold;
  letter-spacing: 2px;
  text-transform: uppercase;
}

/* NAVIGATION */

header {
  background: var(--navy);
  color: var(--white);
  position: sticky;
  top: 0;
  z-index: 100;
  border-bottom: 1px solid #ffffff20;
}

.nav {
  min-height: 78px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
}

.brand {
  display: flex;
  align-items: center;
  gap: 12px;
  min-width: 0;
}

.brand-symbol {
  width: 43px;
  height: 43px;
  border: 1px solid var(--gold);
  display: grid;
  place-items: center;
  color: var(--gold);
  font: 27px Georgia, serif;
  flex-shrink: 0;
}

.brand-name {
  font: 16px Georgia, serif;
  line-height: 1.3;
}

.brand-name small {
  display: block;
  font: 9px Arial, sans-serif;
  letter-spacing: 1.6px;
  color: #e1cfaa;
  margin-top: 5px;
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 23px;
}

.nav-links a {
  color: #e1e6ed;
  font-size: 12px;
}

.nav-links a:hover {
  color: var(--gold);
}

.menu-button {
  display: none;
  background: transparent;
  border: 1px solid #ffffff50;
  color: white;
  padding: 9px 12px;
  cursor: pointer;
}

/* HERO */

.hero {
  background: linear-gradient(120deg, var(--navy), #203956);
  color: white;
  overflow: hidden;
}

.hero-content {
  display: grid;
  grid-template-columns: 1.2fr .8fr;
  align-items: center;
  gap: 55px;
  padding-top: 85px;
  padding-bottom: 85px;
}

.hero h1 {
  font: 400 clamp(40px, 5.3vw, 68px)/1.13 Georgia, serif;
  letter-spacing: -1px;
  margin: 22px 0;
}

.hero h1 em {
  color: #e4d0a7;
  font-weight: normal;
}

.hero-description {
  max-width: 610px;
  color: #d0d8e3;
  font-size: 15px;
}

.hero-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 30px;
}

.button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  padding: 13px 18px;
  background: var(--gold);
  color: var(--navy);
  font-size: 12px;
  font-weight: bold;
  border: 1px solid var(--gold);
  cursor: pointer;
}

.button:hover {
  background: #e1c58f;
}

.button-outline {
  color: white;
  background: transparent;
  border-color: #ffffff65;
}

.button-outline:hover {
  background: #ffffff12;
}

.hero-art {
  min-height: 330px;
  border: 1px solid #c9a76b70;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 25px;
  position: relative;
}

.hero-art:before,
.hero-art:after {
  content: "";
  position: absolute;
  width: 40px;
  height: 40px;
  border-color: var(--gold);
  border-style: solid;
}

.hero-art:before {
  top: -1px;
  left: -1px;
  border-width: 2px 0 0 2px;
}

.hero-art:after {
  bottom: -1px;
  right: -1px;
  border-width: 0 2px 2px 0;
}

.justice-symbol {
  color: var(--gold);
  font: 125px Georgia, serif;
  line-height: 1.3;
}

.hero-art p {
  font: 19px Georgia, serif;
  color: #eadcbd;
}

/* QUICK BENEFITS */

.benefits {
  background: var(--cream);
  border-bottom: 1px solid var(--border);
}

.benefits-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 25px;
  padding-top: 25px;
  padding-bottom: 25px;
}

.benefit {
  display: flex;
  align-items: center;
  gap: 13px;
}

.benefit-icon {
  width: 40px;
  height: 40px;
  display: grid;
  place-items: center;
  color: var(--green);
  background: #e4ece5;
  font: 23px Georgia, serif;
  flex-shrink: 0;
}

.benefit strong {
  display: block;
  font-size: 12px;
}

.benefit span {
  color: var(--muted);
  font-size: 11px;
}

/* GENERAL SECTIONS */

.section {
  padding: 75px 0;
}

.section-heading {
  max-width: 720px;
  margin-bottom: 32px;
}

.section-heading h2 {
  font: 400 clamp(30px, 4vw, 44px)/1.2 Georgia, serif;
  color: var(--navy);
  margin: 12px 0;
}

.section-heading p {
  font-size: 14px;
  color: var(--muted);
}

/* SEARCH AND FILTERS */

.toolbar {
  display: grid;
  grid-template-columns: 1fr 250px;
  gap: 12px;
  padding: 15px;
  background: var(--cream);
  border: 1px solid var(--border);
  margin-bottom: 18px;
}

.toolbar input,
.toolbar select {
  min-width: 0;
  width: 100%;
  padding: 13px;
  border: 1px solid #d8d5ce;
  background: white;
  color: var(--text);
  border-radius: 0;
  font-size: 13px;
}

.result-count {
  font-size: 12px;
  color: var(--muted);
  margin: 12px 0 18px;
}

/* RESOURCE CARDS */

.card-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
}

.card {
  border: 1px solid var(--border);
  background: white;
  padding: 23px;
  display: flex;
  flex-direction: column;
  min-width: 0;
  transition: box-shadow .2s, transform .2s;
}

.card:hover {
  box-shadow: 0 12px 30px #10203912;
  transform: translateY(-3px);
}

.card-top {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 8px;
}

.tag {
  display: inline-block;
  padding: 5px 8px;
  background: #e9f0eb;
  color: var(--green);
  font-size: 9px;
  font-weight: bold;
  letter-spacing: 1px;
}

.card-symbol {
  font: 28px Georgia, serif;
  color: var(--gold);
}

.card h3 {
  font: 400 21px/1.35 Georgia, serif;
  color: var(--navy);
  margin: 17px 0 9px;
}

.card-provider {
  font-size: 11px;
  color: var(--green);
  font-weight: bold;
}

.card p {
  font-size: 12px;
  color: var(--muted);
  flex: 1;
}

.card-link {
  display: inline-block;
  margin-top: 14px;
  padding-top: 13px;
  border-top: 1px solid var(--border);
  color: var(--green);
  font-size: 12px;
  font-weight: bold;
}

.card-link:hover {
  text-decoration: underline;
}

.empty-state {
  padding: 35px 15px;
  color: var(--muted);
  text-align: center;
  border: 1px dashed var(--border);
}

/* CAREER SECTION */

.soft-section {
  background: var(--cream);
}

.pathways {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
}

.pathway {
  background: white;
  border: 1px solid var(--border);
  padding: 26px;
}

.pathway-number {
  font: 29px Georgia, serif;
  color: var(--gold);
}

.pathway h3 {
  font: 400 23px Georgia, serif;
  color: var(--navy);
}

.pathway p {
  color: var(--muted);
  font-size: 12px;
}

.text-link {
  color: var(--green);
  font-size: 12px;
  font-weight: bold;
}

/* ABOUT */

.about-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 45px;
  align-items: center;
}

.about-grid h2 {
  color: var(--navy);
  font: 400 38px/1.25 Georgia, serif;
}

.about-grid p {
  color: var(--muted);
  font-size: 13px;
}

.official-panel {
  background: var(--navy);
  color: white;
  padding: 30px;
}

.official-panel h3 {
  font: 27px Georgia, serif;
}

.official-panel p {
  color: #cbd5e1;
}

.official-panel a {
  display: block;
  padding: 12px 0;
  color: #ead7b0;
  border-bottom: 1px solid #ffffff20;
  font-size: 12px;
}

/* FOOTER */

footer {
  background: #0b1422;
  color: white;
  padding: 40px 0 22px;
}

.footer-top {
  display: flex;
  justify-content: space-between;
  gap: 30px;
  flex-wrap: wrap;
}

.footer-about {
  max-width: 400px;
}

.footer-about p {
  font-size: 12px;
  color: #c1cbd8;
}

.footer-links {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}

.footer-links a {
  color: #d4dce6;
  font-size: 12px;
}

.footer-bottom {
  border-top: 1px solid #ffffff20;
  margin-top: 30px;
  padding-top: 18px;
  font-size: 10px;
  color: #aeb9c9;
}

/* MOBILE */

@media (max-width: 900px) {
  .hero-content {
    gap: 28px;
  }

  .card-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 650px) {
  .nav {
    min-height: 72px;
    flex-wrap: wrap;
    padding: 12px 0;
  }

  .brand-name {
    font-size: 13px;
  }

  .menu-button {
    display: block;
  }

  .nav-links {
    display: none;
    width: 100%;
    flex-direction: column;
    align-items: flex-start;
    gap: 0;
    padding-bottom: 10px;
  }

  .nav-links.open {
    display: flex;
  }

  .nav-links a {
    padding: 10px 0;
  }

  .hero-content {
    grid-template-columns: 1fr;
    padding-top: 55px;
    padding-bottom: 50px;
  }

  .hero-art {
    min-height: 245px;
  }

  .justice-symbol {
    font-size: 85px;
  }

  .benefits-grid {
    grid-template-columns: 1fr;
    gap: 15px;
  }

  .section {
    padding: 55px 0;
  }

  .toolbar {
    grid-template-columns: 1fr;
  }

  .card-grid,
  .pathways,
  .about-grid {
    grid-template-columns: 1fr;
  }

  .about-grid h2 {
    font-size: 32px;
  }
}

@media (prefers-reduced-motion: reduce) {
  html {
    scroll-behavior: auto;
  }

  *, *:before, *:after {
    transition: none !important;
  }
}
</style>
</head>

<body>

<header>
  <nav class="container nav">
    <a href="#home" class="brand">
      <span class="brand-symbol">§</span>
      <span class="brand-name">
        LEGAL LEARNING INSTITUTE SA
        <small>KNOWLEDGE · EXCELLENCE · PROGRESS</small>
      </span>
    </a>

    <button class="menu-button" id="menuButton"
      aria-expanded="false" aria-controls="navLinks">
      ☰ Menu
    </button>

    <div class="nav-links" id="navLinks">
      <a href="#learning">Learning</a>
      <a href="#firms">Law Firms</a>
      <a href="#careers">Career Paths</a>
      <a href="#about">About</a>
    </div>
  </nav>
</header>

<main>

<section class="hero" id="home">
  <div class="container hero-content">
    <div>
      <div class="eyebrow">SOUTH AFRICAN LEGAL DIRECTORY</div>
      <h1>Build your future in <em>South African law.</em></h1>
      <p class="hero-description">
        Discover legal learning opportunities, candidate attorney
        resources, research tools and established law firms.
        Take the next step in your legal career with confidence.
      </p>
      <div class="hero-buttons">
        <a class="button" href="#learning">Explore Legal Resources ↗</a>
        <a class="button button-outline" href="#firms">Find Law Firms</a>
      </div>
    </div>

    <div class="hero-art">
      <div class="justice-symbol">§</div>
      <p>Knowledge is the foundation of justice.</p>
      <div class="eyebrow">LEARN · DEVELOP · ADVANCE</div>
    </div>
  </div>
</section>

<section class="benefits">
  <div class="container benefits-grid">
    <div class="benefit">
      <div class="benefit-icon">§</div>
      <div>
        <strong>South African Focus</strong>
        <span>Local legal study and research</span>
      </div>
    </div>
    <div class="benefit">
      <div class="benefit-icon">◇</div>
      <div>
        <strong>Trusted Starting Points</strong>
        <span>Links to official organisations</span>
      </div>
    </div>
    <div class="benefit">
      <div class="benefit-icon">↗</div>
      <div>
        <strong>Career Exploration</strong>
        <span>Discover firms and opportunities</span>
      </div>
    </div>
  </div>
</section>

<section class="section" id="learning">
  <div class="container">
    <div class="section-heading">
      <div class="eyebrow">THE LEARNING DIRECTORY</div>
      <h2>Invest in your legal future.</h2>
      <p>
        Search South African legal resources, professional bodies
        and online courses. Each link opens the relevant external
        website, where you can check availability and requirements.
      </p>
    </div>

    <div class="toolbar">
      <input id="resourceSearch" type="search"
        placeholder="Search legal resources..."
        aria-label="Search legal resources">

      <select id="resourceFilter" aria-label="Filter resources">
        <option value="all">All categories</option>
        <option value="training">Candidate attorney training</option>
        <option value="research">Research and legislation</option>
        <option value="courses">Online courses</option>
        <option value="professional">Professional organisations</option>
      </select>
    </div>

    <div class="result-count" id="resourceCount" aria-live="polite"></div>
    <div class="card-grid" id="resourceGrid"></div>
    <div class="empty-state" id="resourceEmpty" hidden>
      No resources found. Try another search or category.
    </div>

    <p class="result-count">
      Note: Some links provide legal research or regulatory
      information rather than courses. Check course fees,
      accreditation and certificate requirements with providers.
    </p>
  </div>
</section>

<section class="section soft-section" id="firms">
  <div class="container">
    <div class="section-heading">
      <div class="eyebrow">SOUTH AFRICAN LAW FIRMS</div>
      <h2>Discover established legal practices.</h2>
      <p>
        Explore official firm websites to learn about their services,
        practice areas, graduate programmes and candidate attorney
        application processes.
      </p>
    </div>

    <div class="toolbar">
      <input id="firmSearch" type="search"
        placeholder="Search law firms or practice areas..."
        aria-label="Search law firms">

      <select id="firmFilter" aria-label="Filter law firms">
        <option value="all">All law firms</option>
        <option value="full">Full-service and commercial</option>
        <option value="specialist">Specialist practices</option>
      </select>
    </div>

    <div class="result-count" id="firmCount" aria-live="polite"></div>
    <div class="card-grid" id="firmGrid"></div>
    <div class="empty-state" id="firmEmpty" hidden>
      No firms found. Try another search or category.
    </div>

    <p class="result-count">
      This directory is not a ranking or endorsement. Firm details
      and recruitment opportunities should be verified directly.
    </p>
  </div>
</section>

<section class="section" id="careers">
  <div class="container">
    <div class="section-heading">
      <div class="eyebrow">YOUR PROFESSIONAL JOURNEY</div>
      <h2>Choose your next step.</h2>
      <p>
        Build your knowledge, develop practical skills and learn
        about the professional requirements relevant to your goals.
      </p>
    </div>

    <div class="pathways">
      <article class="pathway">
        <div class="pathway-number">01</div>
        <h3>Law Students</h3>
        <p>
          Strengthen your legal research, writing and understanding
          of South African legislation and case law.
        </p>
        <a class="text-link"
          href="https://www.saflii.org/"
          target="_blank" rel="noopener noreferrer">
          Explore SAFLII ↗
        </a>
      </article>

      <article class="pathway">
        <div class="pathway-number">02</div>
        <h3>Candidate Attorneys</h3>
        <p>
          Review official training manuals and check current
          practical vocational training and examination requirements.
        </p>
        <a class="text-link"
          href="https://lpc.org.za/"
          target="_blank" rel="noopener noreferrer">
          Visit the LPC ↗
        </a>
      </article>

      <article class="pathway">
        <div class="pathway-number">03</div>
        <h3>Legal Practitioners</h3>
        <p>
          Investigate professional development opportunities and
          verify applicable continuing professional development
          requirements with the regulator.
        </p>
        <a class="text-link"
          href="https://www.lpc.org.za/"
          target="_blank" rel="noopener noreferrer">
          Professional resources ↗
        </a>
      </article>
    </div>
  </div>
</section>

<section class="section soft-section" id="about">
  <div class="container about-grid">
    <div>
      <div class="eyebrow">ABOUT THIS DIRECTORY</div>
      <h2>Your ambitions deserve a strong foundation.</h2>
      <p>
        Legal Learning Institute SA is an independent educational
        directory designed to help people explore South African
        legal study, professional resources and career options.
      </p>
      <p>
        General online courses do not automatically qualify a person
        for admission as a legal practitioner or satisfy professional
        training requirements. Verify formal recognition with the
        relevant institution or regulator.
      </p>
    </div>

    <div class="official-panel">
      <div class="eyebrow">USEFUL OFFICIAL SOURCES</div>
      <h3>Start with reliable resources.</h3>
      <p>Explore legislation, judgments and professional information.</p>

      <a href="https://www.lpc.org.za/"
        target="_blank" rel="noopener noreferrer">
        Legal Practice Council ↗
      </a>
      <a href="https://www.saflii.org/"
        target="_blank" rel="noopener noreferrer">
        SAFLII — Legal Research ↗
      </a>
      <a href="https://www.gov.za/"
        target="_blank" rel="noopener noreferrer">
        South African Government ↗
      </a>
      <a href="https://www.justice.gov.za/"
        target="_blank" rel="noopener noreferrer">
        Department of Justice ↗
      </a>
      <a href="https://www.lssa.org.za/"
        target="_blank" rel="noopener noreferrer">
        Law Society of South Africa ↗
      </a>
    </div>
  </div>
</section>

</main>

<footer>
  <div class="container">
    <div class="footer-top">
      <div class="footer-about">
        <div class="brand">
          <span class="brand-symbol">§</span>
          <span class="brand-name">
            LEGAL LEARNING INSTITUTE SA
            <small>KNOWLEDGE · EXCELLENCE · PROGRESS</small>
          </span>
        </div>
        <p>
          An independent directory for South African legal education
          and career exploration.
        </p>
      </div>

      <div class="footer-links">
        <a href="#learning">Resources</a>
        <a href="#firms">Law Firms</a>
        <a href="#careers">Career Paths</a>
        <a href="#about">About</a>
      </div>
    </div>

    <div class="footer-bottom">
      © <span id="year"></span> Legal Learning Institute SA.
      Independent directory. Not a law firm, university or regulator.
      No affiliation with listed organisations is implied.
    </div>
  </div>
</footer>

<script>
"use strict";

/* =================================
   RESOURCE DIRECTORY
================================= */

var resources = [
  {
    title: "Candidate Attorney Training Manuals",
    provider: "Legal Practice Council",
    category: "training",
    tag: "PROFESSIONAL TRAINING",
    symbol: "§",
    description: "Find training manuals and study resources relevant to candidate attorneys. Confirm current requirements with the regulator.",
    url: "https://lpc.org.za/"
  },
  {
    title: "Legal Practice Council",
    provider: "LPC",
    category: "professional",
    tag: "OFFICIAL REGULATOR",
    symbol: "⚖",
    description: "Official information about legal practitioners, professional regulation, admission and relevant requirements.",
    url: "https://www.lpc.org.za/"
  },
  {
    title: "South African Case Law",
    provider: "SAFLII",
    category: "research",
    tag: "LEGAL RESEARCH",
    symbol: "§",
    description: "Access South African judgments and other legal materials for study and legal research.",
    url: "https://www.saflii.org/"
  },
  {
    title: "South African Legislation",
    provider: "Department of Justice",
    category: "research",
    tag: "LEGISLATION",
    symbol: "📚",
    description: "Visit the Department of Justice for legislation and justice-sector information.",
    url: "https://www.justice.gov.za/"
  },
  {
    title: "South African Government",
    provider: "gov.za",
    category: "research",
    tag: "GOVERNMENT",
    symbol: "◇",
    description: "Explore official government information, publications, policies and public resources.",
    url: "https://www.gov.za/"
  },
  {
    title: "Online Law Courses",
    provider: "edX",
    category: "courses",
    tag: "ONLINE LEARNING",
    symbol: "✎",
    description: "Browse online law courses and programs. Availability, fees and qualifications vary by provider.",
    url: "https://www.edx.org/learn/law"
  },
  {
    title: "Legal Studies and Law",
    provider: "Coursera",
    category: "courses",
    tag: "ONLINE LEARNING",
    symbol: "§",
    description: "Search for online learning in legal topics such as contracts, business law and human rights.",
    url: "https://www.coursera.org/search?query=law"
  },
  {
    title: "Law Society of South Africa",
    provider: "LSSA",
    category: "professional",
    tag: "PROFESSIONAL BODY",
    symbol: "⚖",
    description: "Explore professional resources and information connected with the South African legal profession.",
    url: "https://www.lssa.org.za/"
  },
  {
    title: "Constitutional Court",
    provider: "Constitutional Court of South Africa",
    category: "research",
    tag: "JUDICIARY",
    symbol: "§",
    description: "Visit the Constitutional Court website for court information and related resources.",
    url: "https://www.concourt.org.za/"
  }
];

/* =================================
   LAW FIRM DIRECTORY

   These links point to firm websites.
   Check each firm's own careers page
   for current application information.
================================= */

var firms = [
  {
    name: "ENS",
    type: "full",
    area: "African corporate and commercial legal services",
    url: "https://www.ensafrica.com/"
  },
  {
    name: "Bowmans",
    type: "full",
    area: "Corporate law, commercial transactions and disputes",
    url: "https://bowmanslaw.com/"
  },
  {
    name: "Webber Wentzel",
    type: "full",
    area: "Commercial legal services and tax",
    url: "https://www.webberwentzel.com/"
  },
  {
    name: "Cliffe Dekker Hofmeyr",
    type: "full",
    area: "Corporate law, litigation and commercial services",
    url: "https://www.cliffedekkerhofmeyr.com/"
  },
  {
    name: "Werksmans Attorneys",
    type: "full",
    area: "Commercial law, disputes and corporate advisory",
    url: "https://werksmans.com/"
  },
  {
    name: "Norton Rose Fulbright",
    type: "full",
    area: "International business law and commercial practice",
    url: "https://www.nortonrosefulbright.com/en-za"
  },
  {
    name: "Baker McKenzie",
    type: "full",
    area: "International business and commercial legal services",
    url: "https://www.bakermckenzie.com/"
  },
  {
    name: "DLA Piper",
    type: "full",
    area: "International and African business law",
    url: "https://www.dlapiper.com/"
  },
  {
    name: "Fasken",
    type: "full",
    area: "Business law and commercial legal services",
    url: "https://www.fasken.com/"
  },
  {
    name: "Adams & Adams",
    type: "specialist",
    area: "Intellectual property and commercial law",
    url: "https://www.adams.africa/"
  },
  {
    name: "Spoor & Fisher",
    type: "specialist",
    area: "Intellectual property law",
    url: "https://spoor.com/"
  },
  {
    name: "Cheadle Thompson & Haysom",
    type: "specialist",
    area: "Labour law and employment relations",
    url: "https://www.cth.co.za/"
  }
];

/* =================================
   HTML SAFETY HELPER
================================= */

function escapeHTML(value) {
  return String(value).replace(/[&<>"']/g, function(character) {
    var entities = {
      "&": "&amp;",
      "<": "&lt;",
      ">": "&gt;",
      '"': "&quot;",
      "'": "&#39;"
    };

    return entities[character];
  });
}

/* =================================
   RENDER RESOURCES
================================= */

function renderResources() {
  var searchInput = document.getElementById("resourceSearch");
  var filterInput = document.getElementById("resourceFilter");
  var grid = document.getElementById("resourceGrid");
  var count = document.getElementById("resourceCount");
  var empty = document.getElementById("resourceEmpty");

  var query = searchInput.value.toLowerCase().trim();
  var category = filterInput.value;

  var matches = resources.filter(function(item) {
    var text = [
      item.title,
      item.provider,
      item.category,
      item.tag,
      item.description
    ].join(" ").toLowerCase();

    var matchesText = text.indexOf(query) !== -1;
    var matchesCategory =
      category === "all" || item.category === category;

    return matchesText && matchesCategory;
  });

  grid.innerHTML = matches.map(function(item) {
    return `
      <article class="card">
        <div class="card-top">
          <span class="tag">${escapeHTML(item.tag)}</span>
          <span class="card-symbol">${escapeHTML(item.symbol)}</span>
        </div>
        <h3>${escapeHTML(item.title)}</h3>
        <div class="card-provider">${escapeHTML(item.provider)}</div>
        <p>${escapeHTML(item.description)}</p>
        <a class="card-link"
           href="${escapeHTML(item.url)}"
           target="_blank"
           rel="noopener noreferrer">
          Visit resource ↗
        </a>
      </article>
    `;
  }).join("");

  count.textContent =
    matches.length + (matches.length === 1 ?
    " resource found" : " resources found");

  empty.hidden = matches.length !== 0;
  grid.hidden = matches.length === 0;
}

/* =================================
   RENDER LAW FIRMS
================================= */

function renderFirms() {
  var searchInput = document.getElementById("firmSearch");
  var filterInput = document.getElementById("firmFilter");
  var grid = document.getElementById("firmGrid");
  var count = document.getElementById("firmCount");
  var empty = document.getElementById("firmEmpty");

  var query = searchInput.value.toLowerCase().trim();
  var category = filterInput.value;

  var matches = firms.filter(function(firm) {
    var text = (firm.name + " " + firm.area).toLowerCase();
    var matchesText = text.indexOf(query) !== -1;
    var matchesCategory =
      category === "all" || firm.type === category;

    return matchesText && matchesCategory;
  });

  grid.innerHTML = matches.map(function(firm) {
    var typeLabel = firm.type === "specialist" ?
      "SPECIALIST PRACTICE" : "LAW FIRM";

    return `
      <article class="card">
        <div class="card-top">
          <span class="tag">${typeLabel}</span>
          <span class="card-symbol">§</span>
        </div>
        <h3>${escapeHTML(firm.name)}</h3>
        <p>${escapeHTML(firm.area)}</p>
        <a class="card-link"
           href="${escapeHTML(firm.url)}"
           target="_blank"
           rel="noopener noreferrer">
          Visit official website ↗
        </a>
      </article>
    `;
  }).join("");

  count.textContent =
    matches.length + (matches.length === 1 ?
    " firm found" : " firms found");

  empty.hidden = matches.length !== 0;
  grid.hidden = matches.length === 0;
}

/* =================================
   MOBILE NAVIGATION
================================= */

var menuButton = document.getElementById("menuButton");
var navLinks = document.getElementById("navLinks");

menuButton.addEventListener("click", function() {
  var isOpen =
    menuButton.getAttribute("aria-expanded") === "true";

  menuButton.setAttribute("aria-expanded", String(!isOpen));
  navLinks.classList.toggle("open", !isOpen);
});

navLinks.querySelectorAll("a").forEach(function(link) {
  link.addEventListener("click", function() {
    navLinks.classList.remove("open");
    menuButton.setAttribute("aria-expanded", "false");
  });
});

/* =================================
   START WEBSITE
================================= */

document.getElementById("year").textContent =
  new Date().getFullYear();

document.getElementById("resourceSearch")
  .addEventListener("input", renderResources);

document.getElementById("resourceFilter")
  .addEventListener("change", renderResources);

document.getElementById("firmSearch")
  .addEventListener("input", renderFirms);

document.getElementById("firmFilter")
  .addEventListener("change", renderFirms);

renderResources();
renderFirms();
</script>

</body>
</html>
