---
layout: sbx_main
title: Contact Us
permalink: /contact
---

<section class="py-5">
  <div class="container">

    <h1 class="fw-bold mb-3">Let’s Talk</h1>

    <p class="text-muted col-lg-8 mb-4">
      Have a question, idea, or project in mind? We’d love to hear from you.
      Reach out to us through any of the channels below.
    </p>

  </div>
</section>

<!-- CONTACT OPTIONS -->
<section class="pb-5">
  <div class="container">

    <div class="row g-4">

      <!-- EMAIL -->
      <div class="col-md-6">
        <div class="card h-100 shadow-sm ngqms-card">
          <div class="card-body">

            <h5 class="fw-bold mb-3">Email Us</h5>

            <p class="text-muted">
              Send us an email and we’ll get back to you as soon as possible.
            </p>

            <p class="fw-bold mb-3">
              enquiry@softbridge.com.my
            </p>

            <a href="mailto:enquiry@softbridge.com.my"
               class="btn btn-primary">
              Send Email
            </a>

          </div>
        </div>
      </div>

      <!-- LIVE CHAT -->
      <div class="col-md-6">
        <div class="card h-100 shadow-sm ngqms-card">
          <div class="card-body">

            <h5 class="fw-bold mb-3">Live Chat</h5>

            <p class="text-muted">
              Need a quick answer? Chat with us directly through our website.
            </p>

            <p class="fw-bold mb-3">
              Available during business hours
            </p>

            <button class="btn btn-outline-primary"
                    onclick="openTawkTo()">
              Start Chat
            </button>

          </div>
        </div>
      </div>

    </div>

  </div>
</section>

<!-- CTA -->
<section class="py-5 bg-light">
  <div class="container text-center">

    <h2 class="fw-bold mb-3">
      Let’s build something meaningful together.
    </h2>

    <p class="text-muted mb-4">
      Whether it’s a system, solution, or idea — we’re here to help.
    </p>

    <a href="mailto:enquiry@softbridge.com.my"
       class="btn btn-primary btn-lg">
      Get in Touch
    </a>

  </div>
</section>

<script>
function openTawkTo() {
  if (window.Tawk_API) {
    window.Tawk_API.maximize();
  } else {
    alert("Live chat is loading, please try again shortly.");
  }
}
</script>
