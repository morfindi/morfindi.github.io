<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>David E Morfin Diaz — Lead MuleSoft Developer</title>
  <meta name="description" content="Resume — David E Morfin Diaz, Lead MuleSoft Developer" />
  <style>
    :root{
      --bg:#f6f8fb;
      --card:#ffffff;
      --muted:#6b7280;
      --accent:#0f172a;
      --primary:#1f2937;
      --gap:18px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background:linear-gradient(180deg, #f8fafc 0%, var(--bg) 100%);
      color:var(--primary);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:28px;
      display:flex;
      justify-content:center;
      font-size:16px;
      line-height:1.45;
    }
    .container{
      width:100%;
      max-width:980px;
    }
    header.card{
      background:var(--card);
      border-radius:12px;
      padding:24px;
      box-shadow:0 6px 20px rgba(16,24,40,0.06);
      display:flex;
      gap:16px;
      align-items:center;
      margin-bottom:var(--gap);
    }
    .avatar{
      width:96px;height:96px;border-radius:12px;
      background:linear-gradient(135deg,#e6eef8,#edf7f2);
      display:flex;align-items:center;justify-content:center;
      font-weight:700;color:var(--accent);font-size:28px;
    }
    .title h1{margin:0;font-size:20px}
    .title p{margin:6px 0 0;color:var(--muted);font-size:14px}
    .contact{
      margin-left:auto;
      text-align:right;
      font-size:14px;
      color:var(--muted);
    }
    .contact a{color:inherit;text-decoration:none}
    main{
      display:grid;
      grid-template-columns: 1fr 340px;
      gap:18px;
    }
    .card{
      background:var(--card);
      border-radius:12px;
      padding:20px;
      box-shadow:0 6px 20px rgba(16,24,40,0.04);
    }
    .section-title{font-weight:700;margin:0 0 12px 0}
    .muted{color:var(--muted)}
    /* left column content */
    .experience .job{margin-bottom:16px}
    .job .job-head{display:flex;justify-content:space-between;gap:12px}
    .job h3{margin:0;font-size:16px}
    .job .meta{font-size:13px;color:var(--muted)}
    ul.skills{list-style:none;padding-left:0;margin:8px 0 0 0;display:flex;flex-wrap:wrap;gap:8px}
    ul.skills li{background:#eef2ff;padding:6px 10px;border-radius:8px;font-size:13px;color:#1e293b}
    .cert-list, .edu-list{margin:0;padding-left:16px}
    .links a{display:inline-block;margin-right:8px;color:var(--primary);text-decoration:none}
    .right-column .card + .card{margin-top:var(--gap)}
    .community a{display:block;margin-bottom:6px;color:#0b56d2;word-break:break-all}
    /* small screens */
    @media (max-width:880px){
      main{grid-template-columns:1fr}
      .contact{text-align:left;margin-top:12px}
      header.card{flex-direction:column;align-items:flex-start}
    }
  </style>
</head>
<body>
  <div class="container" role="main">
    <header class="card" aria-label="Resume header">
      <div class="avatar" aria-hidden="true">DM</div>
      <div class="title">
        <h1>David E Morfin Diaz</h1>
        <p class="muted">Lead MuleSoft Developer — Columbia, South Carolina</p>
      </div>
      <div class="contact" aria-label="Contact information">
        <div><strong>Email:</strong> <a href="mailto:dmorfindiaz@gmail.com">dmorfindiaz@gmail.com</a></div>
        <div><strong>Phone:</strong> <a href="tel:+1803243059">(803) 243-0592</a></div>
        <div><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/dmorfindiaz/" target="_blank" rel="noopener noreferrer">dmorfindiaz</a></div>
      </div>
    </header>

    <main>
      <!-- Left column -->
      <section class="card" aria-labelledby="summary-heading">
        <h2 id="summary-heading" class="section-title">Experience Summary</h2>
        <p class="muted">
          Cloud Integration Developer specializing in MuleSoft. Experienced integrating SaaS (Salesforce, NetSuite, Workday), databases, message queues (Kafka, AWS SQS, Azure Service Bus, Anypoint MQ) and building APIs with Mule 3 &amp; Mule 4. Skilled with API-led connectivity, CI/CD (GitLab, Maven), testing (MUnit, Postman), performance analysis and production support. Certified MuleSoft Platform Architect and Mule 4 Developer among other certifications.
        </p>

        <h3 class="section-title" style="margin-top:18px">Professional Experience</h3>
        <div class="experience">
          <article class="job" aria-labelledby="job-capg">
            <div class="job-head">
              <h3 id="job-capg">Capgemini — Lead MuleSoft Developer</h3>
              <div class="meta">Columbia, SC — Jan 2021 &mdash; Current</div>
            </div>
            <p class="muted">
              Role: Developer Lead. Led a team of 6 on-shore and 1 off-shore. Provided platform technical leadership, reusable artifacts, Mule 3 &amp; Mule 4 migrations, integrations between Workday, databases, REST/SOAP APIs, SFTP/FTP/SMB, Redis/Object Stores. Configured CI/CD pipelines (GitLab, Maven), used MUnit/Postman/JMeter for testing, and mentored team members.
            </p>
            <ul>
              <li>API design, 3-layer architecture, API security (client-id, OAuth2).</li>
              <li>Production support: thread &amp; performance analysis, scaling, CAB coordination.</li>
              <li>Used object stores and messaging (AWS SQS, Azure Service Bus, Anypoint MQ).</li>
            </ul>
          </article>

          <article class="job" aria-labelledby="job-advic">
            <div class="job-head">
              <h3 id="job-advic">Ad Victoriam Solutions — MuleSoft Developer</h3>
              <div class="meta">Atlanta, GA — Jul 2019 to May 2020</div>
            </div>
            <p class="muted">
              Implemented Salesforce &amp; RabbitMQ integrations, NetSuite integrations, designed error handling and RAML API specs, participated in scrum ceremonies and demos.
            </p>
            <p class="muted"><strong>Tools:</strong> Anypoint Studio, Postman, SoapUI, RabbitMQ, NetSuite, Bitbucket</p>
          </article>

          <article class="job" aria-labelledby="job-capg2018">
            <div class="job-head">
              <h3 id="job-capg2018">Capgemini — MuleSoft Developer</h3>
              <div class="meta">Columbia, SC — Sep 2018 to Jun 2019</div>
            </div>
            <p class="muted">Built Mule apps integrating HTTP, Salesforce, DB, Kafka, MongoDB and improved error handling and unit testing.</p>
          </article>

          <article class="job" aria-labelledby="job-hcl">
            <div class="job-head">
              <h3 id="job-hcl">HCL Technologies — Junior Java Developer</h3>
              <div class="meta">Guadalajara, MX — Mar 2018 to Sep 2019</div>
            </div>
            <p class="muted">Supported Java-based systems (IBM WebSphere), worked with SQL, attended scrum meetings and handled tickets.</p>
          </article>

          <article class="job" aria-labelledby="job-softtek">
            <div class="job-head">
              <h3 id="job-softtek">Softtek — MuleSoft Developer</h3>
              <div class="meta">Guadalajara, MX — Sep 2016 to Mar 2018</div>
            </div>
            <p class="muted">Migration from TIBCO to Mule 3, built &amp; consumed APIs, deployed on CloudHub &amp; on-prem, used Java/Groovy for custom logic, DB integrations, and tools like Maven/Jenkins/GitHub.</p>
          </article>

          <article class="job" aria-labelledby="job-manz">
            <div class="job-head">
              <h3 id="job-manz">Manzanillo City Hall — Technical Support</h3>
              <div class="meta">Manzanillo, Colima, MX — Sep 2014 to Aug 2016</div>
            </div>
            <p class="muted">Maintained municipal database, supported network hardware &amp; operating systems, and handled user requests for the city website.</p>
          </article>
        </div>

        <h3 class="section-title" style="margin-top:18px">Technical Skills</h3>
        <ul class="skills" aria-hidden="false">
          <li>Mule 3 &amp; Mule 4</li>
          <li>Anypoint Studio</li>
          <li>API Design (RAML)</li>
          <li>DataWeave</li>
          <li>CI/CD (GitLab, Maven)</li>
          <li>MUnit, Postman, JMeter</li>
          <li>AWS / Azure messaging</li>
          <li>Salesforce, NetSuite, Workday</li>
          <li>Databases: MySQL, SQL Server, MongoDB</li>
        </ul>

        <h3 class="section-title" style="margin-top:18px">Education</h3>
        <ul class="edu-list">
          <li><strong>Bachelor’s Degree in Software Engineering</strong><br/>University of Colima, School of Telematics — Colima, México (Aug 2010 – Jul 2014)</li>
          <li style="margin-top:8px"><strong>Certification in Information and Communication Technologies</strong><br/>University of Colima — Sep 2016 – Nov 2016</li>
        </ul>

        <h3 class="section-title" style="margin-top:18px">Certifications</h3>
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

      <!-- Right column -->
      <aside class="right-column">
        <div class="card" aria-labelledby="side-head">
          <h2 id="side-head" class="section-title">Quick Info</h2>
          <p class="muted"><strong>Location:</strong> Columbia, South Carolina</p>
          <p class="muted"><strong>Role:</strong> Lead MuleSoft Developer / Integration Architect</p>
          <p class="muted"><strong>Languages:</strong> English, Spanish</p>

          <h3 class="section-title" style="margin-top:12px">Tools &amp; OS</h3>
          <p class="muted">Anypoint Studio, Maven, GitLab, Jenkins, CloudHub, SoapUI, Postman, DBeaver, Toad, SQL Developer, WinSCP</p>

          <h3 class="section-title" style="margin-top:12px">Community &amp; Speaking</h3>
          <div class="community">
            <a href="https://meetups.mulesoft.com/online-group-spanish/" target="_blank" rel="noopener noreferrer">MuleSoft Latin America Meetup (Leader)</a>
            <a href="https://www.youtube.com/channel/UCoBkSA64Zr1uvxmbbeE_zIQ/videos" target="_blank" rel="noopener noreferrer">YouTube Channel — MuleSoft videos</a>
            <a href="https://www.youtube.com/playlist?list=PLGZxPBjw1EoBs6MNSpApg9kaM3EQV47AK" target="_blank" rel="noopener noreferrer">Series: Get certified in Mule 4 (playlist)</a>
          </div>
        </div>

        <div class="card">
          <h3 class="section-title">Notable Projects & Highlights</h3>
          <ul>
            <li>Led API-led integrations for multi-brand restaurant client (Workday, DBs, REST/SOAP, caching & queues).</li>
            <li>Coordinated Mule 3 → Mule 4 migrations and added APIs into CI/CD pipelines.</li>
            <li>Designed reprocessing and error-handling frameworks to improve reliability.</li>
            <li>Speaker and moderator at MuleSoft community events and conferences.</li>
          </ul>
        </div>

        <div class="card">
          <h3 class="section-title">OS &amp; Development Environments</h3>
          <p class="muted">Windows, Mac, Linux — MacBook (development), Windows for testing</p>
        </div>
      </aside>
    </main>

    <footer style="margin-top:18px;text-align:center;color:var(--muted);font-size:13px">
      <p>Resume generated from source document. Last updated: <time datetime="2025-12-11">December 11, 2025</time></p>
    </footer>
  </div>
</body>
</html>
