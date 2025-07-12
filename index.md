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
      <li><strong>Full Papers</strong>: Up to 9 pages (including figures, tables, proofs, appendixes, acknowledgments, and any content except references)
        but excluding references. 
        Present substantial research, theoretical analyses, or comprehensive surveys.</li>
      <li><strong>Short Papers</strong>: Up to 4 pages (including figures, tables, proofs, appendixes, acknowledgments, and any content except references)
        but excluding references. 
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
      <li><strong>Submission Deadline</strong>: <span style="text-decoration: line-through;">April 23, 2025 (AOE)</span> <strong>New:</strong> May 4, 2025 (AOE)</li>
      <li><strong>Notification of Acceptance</strong>: May 21, 2025</li>
      <li><strong>Camera-Ready Deadline</strong>: TBD (instructions still in progress)</li>
      <li><strong>Workshop Date</strong>: July 17, 2025 (During SIGIR 2025)</li>
    </ul>
    <p><em>Exact deadlines may be adjusted to align with SIGIR final scheduling.</em></p>

    <hr>

<h2 id="program">Program</h2>
<table>
  <thead>
    <tr>
      <th>Time</th>
      <th>Event</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>09:00-09:45</td>
      <td>
        <strong>Invited Talk:</strong> <a href="https://czhai.cs.illinois.edu/">ChengXiang Zhai</a> (UIUC)<br>
        <em>"Towards A Unified Agentic Framework for Conversational Information Retrieval and Recommendation: Models, Algorithms, and Evaluation"</em>
      </td>
    </tr>
    <tr>
      <td>09:45-10:30</td>
      <td>
        <strong>Contributed Talks:</strong> <em>"Resources, Evaluation, RAG, and Information Retrieval"</em><br>
        <ul>
          <li><strong>[7 min]</strong> <em>"A Resource for Studying Textual Poisoning Attacks against Embedding-based Retrieval-Augmented Generation in Recommender Systems"</em><br>
          Fatemeh Nazary, Yashar Deldjoo and Tommaso Di Noia</li>
          <li><strong>[7 min]</strong> <em>"FACap: A Large-scale Fashion Dataset for Fine-grained Composed Image Retrieval"</em><br>
          Francois Garderes, Shizhe Chen, Camille-Sovanneary Gauthier and Jean Ponce</li>
          <li><strong>[7 min]</strong> <em>"Exploring Diversity, Novelty, and Popularity Bias in ChatGPT’s Recommendations"</em><br>
          Dario Di Palma, Giovanni Maria Biancofiore, Vito Walter Anelli, Fedelucio Narducci and Tommaso Di Noia</li>
          <li><strong>[3 min]</strong> <em>"CAL-RAG: Retrieval-Augmented Multi-Agent Generation for Content-Aware Layout Design"</em><br>
          Najmeh Forouzandehmehr, Reza Yousefi Maragheh, Sriram Kollipara, Kai Zhao, Topojoy Biswas, Jianpeng Xu, Evren Korpeoglu and Kannan Achan</li>
          <li><strong>[3 min]</strong> <em>"MIND: Memory-Informed & INteractive Dynamic RAG for Multi-Hop Question Answering"</em><br>
          Yuelyu Ji, Rui Meng, Zhuochun Li and Daqing He</li>
          <li><strong>[3 min]</strong> <em>"Multilingual Information Retrieval with a Monolingual Knowledge Base"</em><br>
          Yingyin Zhuang, Aman Gupta and Anurag Beniwal</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>10:30-11:00</td>
      <td>Coffee Break</td>
    </tr>
    <tr>
      <td>11:00-11:45</td>
      <td>
        <strong>Invited Talk:</strong> <a href="https://cseweb.ucsd.edu/~jmcauley">Julian McAuley</a> (UCSD)<br>
        <em>"What's still hard about conversational recommendation?"</em>
      </td>
    </tr>
    <tr>
      <td>11:45-12:33</td>
      <td>
        <strong>Contributed Talks:</strong> <em>"Generative Models for Conversation and Recommendation"</em><br>
        <ul>
          <li><strong>[7 min]</strong> <em>"Synthetic Dialogue Generation for Interactive Conversational Elicitation & Recommendation (ICER)"</em><br>
          Moonkyung Ryu, Chih-Wei Hsu, Yinlam Chow, Mohammad Ghavamzadeh and Craig Boutilier</li>
          <li><strong>[7 min]</strong> <em>"ARAG: Agentic Retrieval Augmented Generation for Personalized Recommendation"</em><br>
          Reza Yousefi Maragheh, Pratheek Vadla, Priyank Gupta, Kai Zhao, Aysenur Inan, Kehui Yao, Jianpeng Xu, Praveen Kanumala, Jason Cho and Sushant Kumar</li>
          <li><strong>[7 min]</strong> <em>"Think Before Recommend: Unleashing the Latent Reasoning Power for Sequential Recommendation"</em><br>
          Jiakai Tang, Sunhao Dai, Teng Shi, Jun Xu, Xu Chen, Wen Chen, Jian Wu and Yuning Jiang</li>
          <li><strong>[3 min]</strong> <em>"LLM-based User Profile Management for Recommender System"</em><br>
          Seunghwan Bang and Hwanjun Song</li>
          <li><strong>[3 min]</strong> <em>"Personalized Conversational Recommendations via Prompt tuning and Knowledge Injection<"</em><br>
          Noriaki Kawamae</li>
          <li><strong>[3 min]</strong> <em>"How Does Multimodal Training Affect Text-Only Recommendation Capabilities of LLMs: A Comparative Analysis"</em><br>
          Mert Atay, Ismail Hakki Toroslu, Ismail Sengor Altingovde and Pinar Karagoz</li>
          <li><strong>[3 min]</strong> <em>"Asking Clarifying Questions for Preference Elicitation With Large Language Models"</em><br>
          Ali Montazeralghaem, Guy Tennenholtz, Craig Boutilier and Ofer Meshi</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>12:33-12:40</td>
      <td><strong>Wrap-up and Future Directions</strong></td>
    </tr>
<!--
    <tr>
      <td>12:33-1</td>
      <td><strong>Lunch (on your own)</strong></td>
    </tr>
-->
    <tr>
      <td>13:00-14:30</td>
      <td><strong>Joint SIGIR Workshops Poster Session (<a href="https://sigir2025.dei.unipd.it/posters.html">poster instructions</a>)</strong></td>
    </tr>
  </tbody>
</table>

    <hr>

    <h2 id="featured-speakers">Invited Speakers</h2>
    <ul>
      <li><strong>Keynote 1</strong>: <em><a href="https://czhai.cs.illinois.edu/">ChengXiang Zhai</a> (UIUC)</em><br>
        <em>"Towards A Unified Agentic Framework for Conversational Information Retrieval and Recommendation: Models, Algorithms, and Evaluation"</em></li>
      <li><strong>Keynote 2</strong>: <em><a href="https://cseweb.ucsd.edu/~jmcauley">Julian McAuley</a> (UCSD)</em><br>
        <em>"What's still hard about conversational recommendation?"</em></li>
    </ul>

    <hr>

    <h2 id="organizers">Workshop Organizers</h2>
    <ul>
      <li><strong>Yashar Deldjoo</strong>, Tenure-Track Assistant Professor, Polytechnic University of Bari, Italy</li>
      <li><strong>Julian McAuley</strong>, Professor, UC San Diego, USA</li>
      <li><strong>Scott Sanner</strong>, Professor, University of Toronto, Canada</li>
      <li><strong>Pablo Castells</strong>, Professor, Autonomous University of Madrid, Spain</li>
      <li><strong>Shuai Zhang</strong>, Applied Scientist, Amazon Web Services AI, USA</li>
      <li><strong>Enrico Palumbo</strong>, Senior Research Scientist, Spotify</li>
      <li><strong>Hugues Bouchard</strong>, Senior Research Manager, Spotify</li>
    </ul>

    <hr>

    <h2 id="committee">Program Committee (Partial List)</h2>
    <ul>
    <!--
      <li>Michael Ekstrand, Drexel University</li>
      <li>Craig Boutilier, Google Research</li>
      <li>Aixin Sun, Nanyang Technological University</li>
      <li>Jianling Wang, Google DeepMind</li>
      <li>(Additional members to be announced)</li>
    -->
      <li>Yupeng Hou (UCSD)</li>
      <li>Rishabh Mehrotra (Sharechat)</li>
      <li>Chengkai Huang (University of New South Wales)</li>
      <li>Mohamed Reda Bouadjenek (Deakin University)</li>
      <li>José Luis Redondo García (Spotify)</li>
      <li>Ali Vardasbi (University of Amsterdam)</li>
      <li>Martin Mladenov (Google Research)</li>
      <li>Branislav Kveton (Amazon)</li>
      <li>Qidong Liu (City University of Hong Kong (CityUHK))</li>
      <li>Azin Ghazimatin (Max Plank Institute)</li>
      <li>Gustavo Penha (Spotify)</li>
    </ul>

    <hr>

    <h2 id="contact">Contact and Further Information</h2>
    <p>For any inquiries, please email:  
    <strong>
  <a href="mailto:gennext_at_sigir2025@googlegroups.com">gennext_at_sigir2025@googlegroups.com</a>
</strong> 
and 
<strong>
  <a href="mailto:deldjooy@acm.org">deldjooy@acm.org</a>
</strong>
    </p>
    <p><em>© 2025 GENNEXT@SIGIR. All rights reserved.</em></p>

  </div><!-- /.content -->
</div><!-- /.wrapper -->
