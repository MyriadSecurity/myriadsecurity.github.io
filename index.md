---
layout: home
title: "Enterprise Security, Built for Small Business"
permalink: /
---

<div class="section">
  <div class="badge">Kansas City • Remote Nationwide</div>
  <h1 style="margin:10px 0 6px">Practical cybersecurity assessments — fast, plain-English, affordable.</h1>
  <p style="color:#a8b3c7">We help small and mid-sized organizations find and fix real risks: vulnerability scans, web app testing, Wi-Fi reviews, and compliance-ready reports.</p>
  <p>
    <a class="btn" href="{{ '/services' | relative_url }}">View Services</a>
    <a class="btn-outline" href="#quote">How It Works</a>
  </p>
</div>

<div class="section">
  <h2>Services</h2>
  <div class="grid-3">
    <div class="card">
      <h3>Security Snapshot</h3>
      <p>2–3 hour checkup, quick scan + top 3 fixes. Ideal for small teams & nonprofits.</p>
      <ul>
        <li>External scan & quick web review</li>
        <li>2-page executive summary</li>
        <li>15-min findings call</li>
      </ul>
    </div>
    <div class="card">
      <h3>Vulnerability Assessment</h3>
      <p>Internal & external scanning with authenticated checks where possible.</p>
      <ul>
        <li>Nmap/OpenVAS scanning</li>
        <li>Prioritized remediation plan</li>
        <li>Follow-up Q&amp;A</li>
      </ul>
    </div>
    <div class="card">
      <h3>Web App Test</h3>
      <p>OWASP-focused testing (Burp/ZAP) for portals, forms, and APIs.</p>
      <ul>
        <li>Auth/session & input validation</li>
        <li>Findings with proofs-of-concept</li>
        <li>Retest included for critical fixes</li>
      </ul>
    </div>
  </div>
</div>

<hr />

<div id="quote" class="section">
  <div class="grid-2">
    <div>
      <h2>Quick Quote</h2>
      <p>Tell us about your environment and we’ll send a fixed-price quote.</p>
    </div>
    <div class="card">
      <!-- Replace YOUR-FORM-ID with your Formspree ID -->
      <form action="https://formspree.io/f/YOUR-FORM-ID" method="POST">
        <div class="grid-2">
          <label>Name<br><input name="name" required></label>
          <label>Email<br><input type="email" name="email" required></label>
        </div>
        <label>Company (optional)<br><input name="company"></label>
        <label>What do you need help with?<br>
          <select name="need">
            <option>Security Snapshot (quick checkup)</option>
            <option>Vulnerability Assessment (internal/external)</option>
            <option>Web App Test</option>
            <option>Wi-Fi Security Review</option>
            <option>Compliance prep (HIPAA/PCI)</option>
          </select>
        </label>
        <label>Notes<br><textarea name="notes" rows="4"></textarea></label>
        <button class="btn" type="submit">Request Quote</button>
        <p style="color:#a8b3c7;font-size:12px;margin-top:8px">By submitting, you agree to our email follow-up. No spam.</p>
      </form>
    </div>
  </div>
</div>
