---
layout: default
title: "GENNEXT Workshop"
---

<!-- Inline CSS for a more polished look -->
<style>
  /* General page layout */
  body {
    margin: 0;
    padding: 0;
    font-family: "Helvetica Neue", Arial, sans-serif;
    background-color: #f5f9fc; /* Updated background color */
    color: #333;
    line-height: 1.6;
  }

  /* A banner/header at the top */
  .banner {
    background-color: #1c8d9c; /* Updated banner color */
    color: white;
    text-align: center;
    padding: 2rem 1rem;
    margin-bottom: 1rem;
  }
  .banner h1 {
    margin: 0.5rem 0;
    font-size: 2.2rem;
  }
  .banner p {
    margin: 0;
    font-size: 1.1rem;
  }

  /* Container for main content + sidebar */
  .wrapper {
    display: flex;
    max-width: 1600px;  /* Increased to 1600px for a much wider layout */
    margin: 0 auto;
    padding: 0 2rem 2rem; /* Added extra padding for better spacing */
  }

  /* Sidebar (table of contents) */
  .sidebar {
    min-width: 250px;
    max-width: 300px; /* Increased sidebar width */
    margin-right: 2rem;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 0 6px rgba(0,0,0,0.1);
    padding: 1rem;
    height: fit-content;
  }
  .sidebar h2 {
    font-size: 1.2rem;
    margin-top: 0;
  }
  .sidebar ul {
    list-style: none;
    padding-left: 0;
  }
  .sidebar ul li {
    margin: 0.4rem 0;
  }
  .sidebar ul li a {
    color: #1c8d9c;
    text-decoration: none;
  }
  .sidebar ul li a:hover {
    text-decoration: underline;
  }

  /* Main content area */
  .content {
    flex: 1;
    background-color: #fff;
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 0 6px rgba(0,0,0,0.1);
    max-width: 1200px;  /* Adjusted to fit the new wider layout */
  }

  /* Headings, spacing adjustments */
  .content h2 {
    margin-top: 1.8rem;
    margin-bottom: 1rem;
  }
  .content h3 {
    margin-top: 1.2rem;
  }

  /* Table styling */
  table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 1.5rem;
  }
  th, td {
    text-align: left;
    padding: 0.5rem;
  }
  th {
    background-color: #f1f1f1;
  }
  tr:nth-child(even) {
    background-color: #fafafa;
  }
</style>

<div class="banner">
  <h1>GENNEXT@SIGIR 2025</h1>
  <p>
    <strong>
      The 1st Workshop on Next Generation of IR and Recommender Systems with Language Agents, Generative Models, 
      and Conversational AI (GENNEXT@SIGIR'25)
    </strong><br>
    Colocated with the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2025)
  </p>
</div>

<div class="wrapper">
  <!-- Sidebar (Table of contents) -->
  <div class="sidebar">
    <h2>Navigation</h2>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#call-for-papers">Call for Papers</a></li>
      <li><a href="#important-dates">Important Dates</a></li>
      <li><a href="#program">Program</a></li>
      <li><a href="#featured-speakers">Featured Speakers</a></li>
      <li><a href="#accepted-papers">Accepted Papers</a></li>
      <li><a href="#organizers">Workshop Organizers</a></li>
      <li><a href="#committee">Program Committee</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </div>

  <!-- Main content -->
  <div class="content">

    <h2 id="home">Home</h2>
    <p>
      Large Language Models (LLMs) and other generative architectures are rapidly reshaping 
      the fields of Information Retrieval (IR) and Recommender Systems (RS). Advanced 
      <em>language agents</em>—which combine LLMs with specialized tool usage, multi-turn dialogue, 
      and domain knowledge—unlock new capabilities such as context-sensitive retrieval, personalized 
      generation, and adaptive conversation flows.
    </p>
    <p>
      Despite the potential benefits, these generative models introduce new challenges in terms 
      of <strong>hallucination</strong>, <strong>bias/fairness</strong>, <strong>data privacy</strong>, 
      <strong>security</strong>, and <strong>evaluation methodologies</strong>. 
      <strong>GENNEXT</strong> aims to explore the intersection of LLM-based <em>language agents</em>, 
      <em>generative content creation</em>, and <em>conversational AI</em> in IR and RS—focusing on 
      risks, opportunities, and novel forms of evaluation and user interaction.
    </p>
    <p>
      Our workshop builds upon the success of the 
      <a href="https://roegen-recsys2024.github.io/" target="_blank">ROEGEN@RecSys'24</a> event 
      but broadens the scope to include more general information retrieval, next-generation 
      recommendation, and tool-augmented LLMs.
    </p>

    <hr>

    <h2 id="call-for-papers">Call for Papers</h2>
    <p>We invite researchers and practitioners to submit work related (but not limited) to:</p>
    <ul>
      <li><strong>LLM-driven IR and Recommender Systems</strong><br>
        Prompting, in-context learning, foundation models, or domain-adaptive fine-tuning for IR/RS.</li>
      <li><strong>Agentic Tool Usage</strong><br>
        Techniques enabling LLMs to call external APIs (e.g., knowledge bases, retrieval models, 
        recommendation engines) to fulfill user queries.</li>
      <li><strong>Conversational and Dialogue Systems</strong><br>
        Multi-turn interactions, user modeling, dynamic preference elicitation, explanation, or 
        negotiation with generative AI.</li>
      <li><strong>Generative Content Creation</strong><br>
        Novel item generation (text, images, music), creative item repurposing, or integrated 
        retrieval-plus-generation frameworks.</li>
      <li><strong>Bias and Fairness, Privacy, and Ethics</strong><br>
        Identifying and mitigating biases in generative models, ensuring privacy, building trust, 
        and tackling hallucination risks.</li>
      <li><strong>Evaluation Metrics and Benchmarks</strong><br>
        Designing new metrics or user study protocols that capture the interplay of generative 
        quality, recommendation relevance, and ethical concerns.</li>
    </ul>

    <h3>Submission Guidelines</h3>
    <ul>
      <li><strong>Full Papers</strong>: Up to 8 pages (excluding references). 
        Present substantial research, theoretical analyses, or comprehensive surveys.</li>
      <li><strong>Short Papers</strong>: Up to 4 pages (excluding references). 
        Suitable for work-in-progress or preliminary findings.</li>
      <li><strong>Extended Abstracts</strong>: 2–3 pages (excluding references). 
        For late-breaking results, vision papers, or discussion proposals.</li>
    </ul>
    <p>
      Submissions must be <strong>anonymized</strong> and follow the official 
      <a href="https://www.acm.org/publications/proceedings-template" target="_blank">
      ACM two-column SIGCONF template</a>.<br>
      All submissions will undergo <strong>double-blind peer review</strong>.
    </p>
    <p>
      Accepted papers will be published in <em>CEUR-WS</em> or a similar open-access venue. 
      Selected high-quality submissions may be invited for extension in a journal special issue.
    </p>
    <p>
      <strong>Submission Link:</strong>  
      <a href="https://easychair.org/my/conference?conf=gennextsigir25" target="_blank">
        EasyChair for GENNEXT@SIGIR'25
      </a>
    </p>

    <hr>

    <h2 id="important-dates">Important Dates (Tentative)</h2>
    <ul>
      <li><strong>Submission Deadline</strong>: April 23, 2025 (AOE)</li>
      <li><strong>Notification of Acceptance</strong>: May 21, 2025</li>
      <li><strong>Camera-Ready Deadline</strong>: June 3, 2025</li>
      <li><strong>Workshop Date</strong>: July 17, 2025 (During SIGIR 2025)</li>
    </ul>
    <p><em>Exact deadlines may be adjusted to align with SIGIR final scheduling.</em></p>

    <hr>

    <h2 id="program">Program (Tentative)</h2>
    <table>
      <thead>
        <tr>
          <th>Time</th>
          <th>Event</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>09:00-09:15</td>
          <td><strong>Opening and Welcome</strong></td>
        </tr>
        <tr>
          <td>09:15-10:00</td>
          <td><strong>Keynote Talk</strong> (Speaker TBA)</td>
        </tr>
        <tr>
          <td>10:00-10:30</td>
          <td><strong>Paper Presentations</strong> (Session I)</td>
        </tr>
        <tr>
          <td>10:30-11:00</td>
          <td>Coffee Break</td>
        </tr>
        <tr>
          <td>11:00-12:15</td>
          <td><strong>Paper Presentations</strong> (Session II)</td>
        </tr>
        <tr>
          <td>12:15-13:30</td>
          <td>Lunch Break</td>
        </tr>
        <tr>
          <td>13:30-14:15</td>
          <td><strong>Keynote Talk</strong> (Speaker TBA)</td>
        </tr>
        <tr>
          <td>14:15-15:30</td>
          <td><strong>Panel Discussion</strong> / Breakout Groups</td>
        </tr>
        <tr>
          <td>15:30-16:00</td>
          <td>Coffee Break</td>
        </tr>
        <tr>
          <td>16:00-17:00</td>
          <td><strong>Poster/Demo Session</strong></td>
        </tr>
        <tr>
          <td>17:00-17:30</td>
          <td><strong>Wrap-up and Future Directions</strong></td>
        </tr>
      </tbody>
    </table>
    <p>
      The final schedule will be posted once we confirm the accepted contributions and keynote speakers.
    </p>

    <hr>

    <h2 id="featured-speakers">Featured Speakers (Tentative)</h2>
    <ul>
      <li><strong>Keynote 1</strong>: <em>TBA</em><br>
        Potential topics: bridging LLMs and IR or generative recommendation at scale.</li>
      <li><strong>Keynote 2</strong>: <em>TBA</em><br>
        Potential topics: addressing fairness, privacy, or hallucinations in generative models.</li>
    </ul>
    <p><em>(Additional speakers to be announced.)</em></p>

    <hr>

    <h2 id="accepted-papers">Accepted Papers</h2>
    <p>A list of accepted papers will be updated here after notifications.</p>

    <hr>

    <h2 id="organizers">Workshop Organizers</h2>
    <ul>
      <li><strong>Yashar Deldjoo</strong>, Tenure-Track Assistant Professor, Polytechnic University of Bari, Italy</li>
      <li><strong>Julian McAuley</strong>, Professor, UC San Diego, USA</li>
      <li><strong>Scott Sanner</strong>, Associate Professor, University of Toronto, Canada</li>
      <li><strong>Pablo Castells</strong>, Professor, Autonomous University of Madrid, Spain</li>
      <li><strong>Shuai Zhang</strong>, Applied Scientist, Amazon Web Services AI, USA</li>
      <li><strong>Enrico Palumbo</strong>, Senior Research Scientist, Spotify</li>
      <li><strong>Hugues Bouchard</strong>, Senior Research Manager, Spotify</li>
    </ul>

    <hr>

    <h2 id="committee">Program Committee (Partial List)</h2>
    <ul>
      <li>Michael Ekstrand, Drexel University</li>
      <li>Craig Boutilier, Google Research</li>
      <li>Aixin Sun, Nanyang Technological University</li>
      <li>Jianling Wang, Google DeepMind</li>
      <li>(Additional members to be announced)</li>
    </ul>

    <hr>

    <h2 id="contact">Contact and Further Information</h2>
    <p>For any inquiries, please email:  
      <strong><a href="mailto:gennext_at_sigir2025@googlegroups.com"gennext_at_sigir2025@googlegroups.com</a></strong>
    </p>
    <p><em>© 2025 GENNEXT@SIGIR. All rights reserved.</em></p>

  </div><!-- /.content -->
</div><!-- /.wrapper -->
