<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>David E Morfin Diaz — Lead MuleSoft Developer</title>
  <meta name="description" content="Resume — David E Morfin Diaz, Lead MuleSoft Developer">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg: #f4f7fb;
      --card-bg: rgba(255, 255, 255, 0.95);
      --accent: #0f52ba;
      --primary: #1f2937;
      --muted: #6b7280;
      --shadow: rgba(16,24,40,0.06);
      --gap: 20px;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Inter', sans-serif;
      line-height: 1.5;
      background: var(--bg);
      color: var(--primary);
      min-height: 100vh;
      padding: 30px;
      display: flex;
      justify-content: center;
    }
    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }

    .container {
      width: 100%;
      max-width: 980px;
      display: flex;
      flex-direction: column;
      gap: var(--gap);
    }

    /* Header */
    header {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      background: var(--card-bg);
      border-radius: 15px;
      padding: 25px;
      box-shadow: 0 8px 24px var(--shadow);
      backdrop-filter: blur(8px);
      gap: 20px;
    }
    .avatar {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      background: linear-gradient(135deg,#e0e8f8,#dceefc);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 32px;
      font-weight: 700;
      color: var(--accent);
      flex-shrink: 0;
    }
    .header-info {
      flex: 1;
    }
    .header-info h1 {
      font-size: 26px;
      margin-bottom: 6px;
    }
    .header-info p {
      font-size: 15px;
      color: var(--muted);
    }
    .contact {
      text-align: right;
      font-size: 14px;
      color: var(--muted);
    }
    .contact div { margin-bottom: 4px; }

    /* Main layout */
    main {
      display: grid;
      grid-template-columns: 1fr 360px;
      gap: var(--gap);
    }

    /* Cards */
    .card {
      background: var(--card-bg);
      border-radius: 15px;
      padding: 22px;
      box-shadow: 0 8px 24px var(--shadow);
      backdrop-filter: blur(8px);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card:hover { transform: translateY(-4px); box-shadow: 0 12px 30px var(--shadow); }

    .section-title { 
      font-weight: 700; 
      margin-bottom: 14px; 
      color: var(--accent);
      border-bottom: 2px solid var(--accent);
      display: inline-block;
      padding-bottom: 4px;
    }

    .muted { color: var(--muted); }

    /* Experience */
    .experience .job { margin-bottom: 18px; }
    .job .job-head {
      display: flex;
      justify-content: space-between;
      align-items: baseline;
      flex-wrap: wrap;
      gap: 10px;
    }
    .job h3 { font-size: 17px; color: var(--primary); }
    .job .meta { font-size: 13px; color: var(--muted); }
    .job ul { margin-top: 6px; padding-left: 20px; list-style: disc; }

    /* Skills */
    ul.skills { 
      list-style: none; 
      padding-left: 0; 
      display: flex; 
      flex-wrap: wrap; 
      gap: 10px; 
      margin-top: 6px;
    }
    ul.skills li {
      background: #e0e7ff;
      padding: 6px 12px;
      border-radius: 8px;
      font-size: 13px;
      color: #1e293b;
    }

    /* Right column */
    aside .card + .card { margin-top: var(--gap); }
    .community a { display: block; margin-bottom: 6px; }

    /* Footer */
    footer { text-align: center; color: var(--muted); font-size: 13px; margin-top: var(--gap); }

    /* Responsive */
    @media(max-width:880px) {
      main { grid-template-columns: 1fr; }
      .contact { text-align: left; margin-top: 10px; }
      header { flex-direction: column; align-items: flex-start; }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header -->
    <header>
      <div class="avatar">DM</div>
      <div class="header-info">
        <h1>David E Morfin Diaz</h1>
        <p>Lead MuleSoft Developer — Columbia, South Carolina</p>
      </div>
      <div class="contact">
        <div>Email: <a href="mailto:dmorfindiaz@gmail.com">dmorfindiaz@gmail.com</a></div>
        <div>Phone: <a href="tel:+1803243059">(803) 243-0592</a></div>
        <div>LinkedIn: <a href="https://www.linkedin.com/in/dmorfindiaz/" target="_blank" rel="noopener noreferrer">dmorfindiaz</a></div>
      </div>
    </header>

    <!-- Main -->
    <main>
      <!-- Left Column -->
      <section class="card">
        <h2 class="section-title">Experience Summary</h2>
        <p class="muted">
          Cloud Integration Developer specializing in MuleSoft. Experienced integrating SaaS (Salesforce, NetSuite, Workday), databases, message queues (Kafka, AWS SQS, Azure Service Bus, Anypoint MQ) and building APIs with Mule 3 & Mule 4. Skilled with API-led connectivity, CI/CD (GitLab, Maven), testing (MUnit, Postman), performance analysis and production support. Certified MuleSoft Platform Architect and Mule 4 Developer among other certifications.
        </p>

        <h2 class="section-title" style="margin-top:18px">Professional Experience</h2>
        <div class="experience">
          <div class="job">
            <div class="job-head">
              <h3>Capgemini — Lead MuleSoft Developer</h3>
              <div class="meta">Columbia, SC — Jan 2021 – Current</div>
            </div>
            <p class="muted">
              Developer Lead. Led a team of 6 on-shore and 1 off-shore. Provided platform technical leadership, reusable artifacts, Mule 3 & Mule 4 migrations, integrations between Workday, databases, REST/SOAP APIs, SFTP/FTP/SMB, Redis/Object Stores. Configured CI/CD pipelines (GitLab, Maven), used MUnit/Postman/JMeter for testing, and mentored team members.
            </p>
            <ul>
              <li>API design, 3-layer architecture, API security (client-id, OAuth2).</li>
              <li>Production support: thread & performance analysis, scaling, CAB coordination.</li>
              <li>Used object stores and messaging (AWS SQS, Azure Service Bus, Anypoint MQ).</li>
            </ul>
          </div>

          <div class="job">
            <div class="job-head">
              <h3>Ad Victoriam Solutions — MuleSoft Developer</h3>
              <div class="meta">Atlanta, GA — Jul 2019 – May 2020</div>
            </div>
            <p class="muted">Implemented Salesforce & RabbitMQ integrations, NetSuite integrations, designed error handling and RAML API specs, participated in scrum ceremonies and demos.</p>
            <p class="muted"><strong>Tools:</strong> Anypoint Studio, Postman, SoapUI, RabbitMQ, NetSuite, Bitbucket</p>
          </div>

          <div class="job">
            <div class="job-head">
              <h3>Capgemini — MuleSoft Developer</h3>
              <div class="meta">Columbia, SC — Sep 2018 – Jun 2019</div>
            </div>
            <p class="muted">Built Mule apps integrating HTTP, Salesforce, DB, Kafka, MongoDB and improved error handling and unit testing.</p>
          </div>

          <div class="job">
            <div class="job-head">
              <h3>HCL Technologies — Junior Java Developer</h3>
              <div class="meta">Guadalajara, MX — Mar 2018 – Sep 2019</div>
            </div>
            <p class="muted">Supported Java-based systems (IBM WebSphere), worked with SQL, attended scrum meetings and handled tickets.</p>
          </div>

          <div class="job">
            <div class="job-head">
              <h3>Softtek — MuleSoft Developer</h3>
              <div class="meta">Guadalajara, MX — Sep 2016 – Mar 2018</div>
            </div>
            <p class="muted">Migration from TIBCO to Mule 3, built & consumed APIs, deployed on CloudHub & on-prem, used Java/Groovy for custom logic, DB integrations, and tools like Maven/Jenkins/GitHub.</p>
          </div>

          <div class="job">
            <div class="job-head">
              <h3>Manzanillo City Hall — Technical Support</h3>
              <div class="meta">Manzanillo, Colima, MX — Sep 2014 – Aug 2016</div>
            </div>
            <p class="muted">Maintained municipal database, supported network hardware & operating systems, and handled user requests for the city website.</p>
          </div>
        </div>

        <h2 class="section-title" style="margin-top:18px">Technical Skills</h2>
        <ul class="skills">
          <li>Mule 3 & Mule 4</li>
          <li>Anypoint Studio</li>
          <li>API Design (RAML)</li>
          <li>DataWeave</li>
          <li>CI/CD (GitLab, Maven)</li>
          <li>MUnit, Postman, JMeter</li>
          <li>AWS / Azure messaging</li>
          <li>Salesforce, NetSuite, Workday</li>
          <li>Databases: MySQL, SQL Server, MongoDB</li>
        </ul>

        <h2 class="section-title" style="margin-top:18px">Education</h2>
        <ul class="edu-list">
          <li><strong>Bachelor’s Degree in Software Engineering</strong><br>University of Colima, School of Telematics — Colima, México (Aug 2010 – Jul 2014)</li>
          <li style="margin-top:6px"><strong>Certification in Information and Communication Technologies</strong><br>University of Colima — Sep 2016 – Nov 2016</li>
        </ul>

        <h2 class="section-title" style="margin-top:18px">Certifications</h2>
        <ul class="cert-list">
          <li>MuleSoft Certified Developer - Mule 4 Level 1 (Feb 2023)</li>
          <li>MuleSoft Go To Market Certification (Feb 2023)</li>
          <li>MuleSoft Certified Platform Architect - Level 1 (Feb 2022)</li>
          <li>Salesforce Administrator (Nov 2020)</li>
          <li>AWS Cloud Practitioner (Jul 2020)</li>
          <li>MCD - API Design Associate (RAML 1.0) (Apr 2019)</li>
          <li>MCD - Integration and API Associate (Mule 3.9) (Mar 2019)</li>
          <li>Scrum Fundamentals Certified — SCRUMstudy (Jan 2017)</li>
          <li>Oracle Certified Associate, Java SE 7 Programmer (Jul 2016)</li>
        </ul>
      </section>

      <!-- Right Column -->
      <aside>
        <div class="card">
          <h2 class="section-title">Quick Info</h2>
          <p class="muted"><strong>Location:</strong> Columbia, SC</p>
          <p class="muted"><strong>Role:</strong> Lead MuleSoft Developer / Integration Architect</p>
          <p class="muted"><strong>Languages:</strong> English, Spanish</p>
        </div>

        <div class="card">
          <h2 class="section-title">Tools & Community</h2>
          <p class="muted">Anypoint Studio, Maven, GitLab, Jenkins, CloudHub, SoapUI, Postman, DBeaver, Toad, SQL Developer, WinSCP</p>
          <div class="community">
            <a href="https://meetups.mulesoft.com/online-group-spanish/" target="_blank">MuleSoft Latin America Meetup (Leader)</a>
            <a href="https://www.youtube.com/channel/UCoBkSA64Zr1uvxmbbeE_zIQ/videos" target="_blank">YouTube Channel — MuleSoft videos</a>
            <a href="https://www.youtube.com/playlist?list=PLGZxPBjw1EoBs6MNSpApg9kaM3EQV47AK" target="_blank">Series: Get certified in Mule 4 (playlist)</a>
          </div>
        </div>

        <div class="card">
          <h2 class="section-title">Notable Projects & Highlights</h2>
          <ul>
            <li>Led API-led integrations for multi-brand restaurant client (Workday, DBs, REST/SOAP, caching & queues).</li>
            <li>Coordinated Mule 3 → Mule 4 migrations and added APIs into CI/CD pipelines.</li>
            <li>Designed reprocessing and error-handling frameworks to improve reliability.</li>
            <li>Speaker and moderator at MuleSoft community events and conferences.</li>
          </ul>
        </div>
      </aside>
    </main>

    <footer>
      <p>Resume generated from source document. Last updated: <time datetime="2025-12-11">December 11, 2025</time></p>
    </footer>
  </div>
</body>
</html>
