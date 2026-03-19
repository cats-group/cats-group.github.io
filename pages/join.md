---
layout: page
title: Join Us
description: "How to join the CATS Lab at the University of Maryland"
permalink: /join/
---

<header class="cats-page-header">
  <h1>Join the CATS Lab</h1>
  <p>We are always looking for motivated students and collaborators</p>
</header>

<div class="container py-5">

  <p class="text-muted mb-5" style="font-size:1.02rem; max-width:720px;">
    We welcome students with backgrounds in Computer Science, Linguistics, Journalism,
    Political Science, Sociology, and related fields. What matters most is curiosity,
    rigor, and a desire to make research with real-world impact.
  </p>

  <div class="row g-4 mb-5">

    <!-- PhD -->
    <div class="col-md-6">
      <div class="join-card h-100">
        <h3><i class="fa-solid fa-graduation-cap me-2" style="color:var(--cats-gold)"></i>Prospective PhD Students</h3>
        <p>
          We admit PhD students through the
          <a href="https://www.cs.umd.edu/grad" target="_blank" rel="noopener">UMD CS PhD program</a>
          (and occasionally through iSchool or Linguistics).
          Applications are reviewed every fall with a December deadline.
        </p>
        <ol>
          <li>Read 2–3 recent papers from the lab to understand our work.</li>
          <li>Email Prof. Smith at <a href="mailto:{{ site.lab.email }}">{{ site.lab.email }}</a> with subject <em>"Prospective PhD – [Your Name]"</em>, a brief statement of interest, your CV, and links to prior work.</li>
          <li>Apply through the official UMD graduate portal; mention the CATS Lab.</li>
          <li>Strong applicants will be invited for an informal video call.</li>
        </ol>
        <a class="btn btn-sm btn-cats mt-3" href="https://www.cs.umd.edu/grad" target="_blank" rel="noopener">
          UMD CS PhD Application <i class="fa-solid fa-arrow-right ms-1"></i>
        </a>
      </div>
    </div>

    <!-- Postdoc -->
    <div class="col-md-6">
      <div class="join-card h-100">
        <h3><i class="fa-solid fa-flask me-2" style="color:var(--cats-gold)"></i>Postdoctoral Researchers</h3>
        <p>
          We occasionally host postdoctoral researchers, especially those with their own
          fellowship funding (NSF, NIH, CIFAR, Marie Skłodowska-Curie, etc.).
        </p>
        <ul>
          <li>Strong publication record in NLP, CSS, or a related area.</li>
          <li>Interest in interdisciplinary, socially-impactful research.</li>
          <li>Ability to mentor graduate students.</li>
        </ul>
        <p>Email Prof. Smith with your CV, a research statement (1–2 pages), and names of three referees.</p>
        <a class="btn btn-sm btn-cats-outline mt-3" href="mailto:{{ site.lab.email }}">
          <i class="fa-solid fa-envelope me-1"></i> Contact Prof. Smith
        </a>
      </div>
    </div>

    <!-- MS -->
    <div class="col-md-6">
      <div class="join-card h-100">
        <h3><i class="fa-solid fa-book me-2" style="color:var(--cats-gold)"></i>Master's Students (UMD)</h3>
        <p>
          Current UMD MS students interested in a thesis or project under CATS Lab supervision
          should follow these steps:
        </p>
        <ol>
          <li>Browse our <a href="{{ '/publications/' | relative_url }}">publications</a> and identify a topic that excites you.</li>
          <li>Attend one of our weekly lab meetings (details on the homepage).</li>
          <li>Send an email to <a href="mailto:{{ site.lab.email }}">{{ site.lab.email }}</a> with your transcript, CV, and a paragraph describing the research question you'd like to explore.</li>
        </ol>
        <p class="mb-0"><em>Note: Early outreach (at least one semester ahead) is strongly encouraged.</em></p>
      </div>
    </div>

    <!-- Undergrad -->
    <div class="col-md-6">
      <div class="join-card h-100">
        <h3><i class="fa-solid fa-lightbulb me-2" style="color:var(--cats-gold)"></i>Undergraduate Researchers</h3>
        <p>
          We offer research experience through independent study credits (CMSC 498),
          the UMD URES program, and informal volunteer positions.
        </p>
        <ul>
          <li>Completion of at least one ML or NLP course (or equivalent experience).</li>
          <li>Proficiency in Python and comfort with reading research papers.</li>
          <li>Commitment of at least 10 hours per week for a full semester.</li>
        </ul>
        <p>Email us with your resume and a brief description of your background and interests.</p>
        <a class="btn btn-sm btn-cats-outline mt-2" href="mailto:{{ site.lab.email }}">
          <i class="fa-solid fa-envelope me-1"></i> Apply Now
        </a>
      </div>
    </div>

  </div><!-- /row -->

  <!-- FAQ -->
  <h2 class="section-title">Frequently Asked Questions</h2>

  <div class="accordion mb-5" id="faqAccordion">

    <div class="accordion-item border mb-2 rounded">
      <h3 class="accordion-header">
        <button class="accordion-button collapsed fw-semibold" type="button" data-bs-toggle="collapse" data-bs-target="#faq1" aria-expanded="false" aria-controls="faq1" style="color:var(--cats-navy)">
          Do I need to contact Prof. Smith before applying to the PhD program?
        </button>
      </h3>
      <div id="faq1" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
        <div class="accordion-body text-muted" style="font-size:.92rem;">
          It is not required, but a brief email introducing yourself and explaining why you want
          to work with us can be helpful — especially if your background is interdisciplinary.
          We read all application files, but a prior introduction ensures your application is flagged.
        </div>
      </div>
    </div>

    <div class="accordion-item border mb-2 rounded">
      <h3 class="accordion-header">
        <button class="accordion-button collapsed fw-semibold" type="button" data-bs-toggle="collapse" data-bs-target="#faq2" aria-expanded="false" aria-controls="faq2" style="color:var(--cats-navy)">
          What programming languages and tools does the lab use?
        </button>
      </h3>
      <div id="faq2" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
        <div class="accordion-body text-muted" style="font-size:.92rem;">
          Python is our primary language. We regularly use HuggingFace Transformers, PyTorch,
          spaCy, NLTK, scikit-learn, and standard data science tools (pandas, numpy, matplotlib).
          Familiarity with Git and basic Linux command-line tools is expected.
        </div>
      </div>
    </div>

    <div class="accordion-item border mb-2 rounded">
      <h3 class="accordion-header">
        <button class="accordion-button collapsed fw-semibold" type="button" data-bs-toggle="collapse" data-bs-target="#faq3" aria-expanded="false" aria-controls="faq3" style="color:var(--cats-navy)">
          Is funding available for PhD students?
        </button>
      </h3>
      <div id="faq3" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
        <div class="accordion-body text-muted" style="font-size:.92rem;">
          Yes. PhD students admitted to our lab are typically fully funded through research or
          teaching assistantships, which cover tuition and a stipend. We also actively support
          students in applying for fellowships (NSF GRFP, NDSEG, etc.).
        </div>
      </div>
    </div>

    <div class="accordion-item border mb-2 rounded">
      <h3 class="accordion-header">
        <button class="accordion-button collapsed fw-semibold" type="button" data-bs-toggle="collapse" data-bs-target="#faq4" aria-expanded="false" aria-controls="faq4" style="color:var(--cats-navy)">
          I am not a CS student. Can I still join the lab?
        </button>
      </h3>
      <div id="faq4" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
        <div class="accordion-body text-muted" style="font-size:.92rem;">
          Absolutely. We value interdisciplinary perspectives and have had students from
          Linguistics, Journalism, Political Science, and Information Science. What matters is
          strong analytical thinking and genuine interest in language and society. Some programming
          experience is expected, but we can help you develop those skills.
        </div>
      </div>
    </div>

  </div><!-- /accordion -->

  <!-- CTA -->
  <div class="contact-cta">
    <h2>Ready to get in touch?</h2>
    <p>We are excited to hear from you. Include your CV and a brief description of your interests.</p>
    <a class="btn btn-gold btn-lg" href="mailto:{{ site.lab.email }}">
      <i class="fa-solid fa-envelope me-2"></i>{{ site.lab.email }}
    </a>
  </div>

</div>
