---
weight: 100
title: "Software Design Patterns in Rust"
description: "New Way of Learning in GenAI Era"
icon: "Menu_Book"
date: "2024-08-13T23:15:27+07:00"
lastmod: "2024-08-13T23:15:27+07:00"
draft: false
toc: true
---

{{< figure src="/images/P8MKxO7NRG2n396LeSEs-GwKBjxxYsu065L5olhOV-v1.png" width="500" height="300" class="text-center" >}}

<center>

### 📘 About this Book

</center>

{{% alert icon="📘" context="info" %}}
<p style="text-align: justify;">
<strong>Software Design Patterns in Rust</strong> is a groundbreaking guide that stands out as the premier modern resource for mastering software design patterns with Rust. This book uniquely integrates Rust’s powerful features, such as its ownership model and type system, with established design patterns, offering readers a contemporary perspective on crafting robust, efficient, and maintainable software. Through practical examples and insightful explanations, it bridges the gap between theory and application, equipping developers with the tools to leverage Rust’s strengths in implementing design patterns effectively. Whether you're new to Rust or a seasoned developer, this book is an essential resource for enhancing your design skills and optimizing your code.
</p>
{{% /alert %}}

<div class="row justify-content-center my-4">
  <div class="col-md-8 col-12">
      <div class="card p-4 text-center support-card">
          <h4 class="mb-3" style="color: #50C878;">SUPPORT US ❤️</h4>
          <p class="card-text">
              Support our mission by purchasing the companion book at your preferred platform.
          </p>
          <div class="d-flex justify-content-center mb-3 flex-wrap">
              <a href="https://www.amazon.com/dp/B0DJCKCGVR" class="btn btn-lg btn-outline-support m-2 support-btn">
                  <img src="../../images/kindle.png" alt="Amazon Logo" class="support-logo-image">
                  <span class="support-btn-text">Buy on Amazon</span>
              </a>
              <a href="https://play.google.com/store/books/details?id=8qglEQAAQBAJ&pli=1" class="btn btn-lg btn-outline-support m-2 support-btn">
                  <img src="../../images/GBooks.png" alt="Google Books Logo" class="support-logo-image">
                  <span class="support-btn-text">Buy on Google Books</span>
              </a>
          </div>
      </div>
  </div>
</div>

<style>
  .btn-outline-support {
      color: #50C878;
      border: 2px solid #50C878;
      background-color: transparent;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 25px; /* Increased padding for a more prominent button */
      width: 200px; /* Increased width for better visibility */
      text-align: center;
      transition: all 0.3s ease-in-out; /* Smooth transition for hover effects */
  }
  .btn-outline-support:hover {
      background-color: #50C878;
      color: white;
      border-color: #50C878;
  }
  .support-logo-image {
      max-width: 100%;
      height: auto;
      margin-bottom: 16px; /* Increased space between the logo and the button text */
  }
  .support-btn {
      width: 300px; /* Increased width for both buttons */
  }
  .support-btn-text {
      font-weight: bold;
      font-size: 1.1rem; /* Slightly larger text for better readability */
  }
  .support-card {
      transition: box-shadow 0.3s ease-in-out;
  }
  .support-card:hover {
      box-shadow: 0 0 20px #50C878; /* Green glowing border effect when hovered */
  }
</style>

<center>

## 🚀 About RantAI

</center>

<div class="row justify-content-center">
    <div class="col-md-4 col-12 py-2">
        <a class="text-decoration-none text-reset" href="https://www.linkedin.com/in/rantai/">
            <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1 text-center">
                <img src="../../images/Logo.png" class="card-img-top" alt="Rantai Logo">
            </div>
        </a>
    </div>
</div>

{{% alert icon="🚀" context="success" %}}
<p style="text-align: justify;">
RantAI started as a pioneer in open book publishing for scientific computing, setting the standard for technological innovation. As a premier System Integrator (SI), we specialize in addressing complex scientific challenges through advanced Machine Learning, Deep Learning, Agent-Based Modeling, and AI Chip Development based on the RISC-V architecture. Our proficiency in AI-driven coding and optimization enables us to deliver comprehensive, end-to-end scientific simulation and digital twin solutions. At RantAI, we are dedicated to pushing the boundaries of technology, delivering cutting-edge solutions to tackle the world’s most critical scientific problems.Through our open publications, we connect with top talent, customers, and partners, using these works as a strategic arm to advance scientific computing and innovation.</p>
{{% /alert %}}

<center>

## 👥 SDPR Authors

</center>

<div class="row flex-xl-wrap pb-4">
    <div class="col-md-4 col-12 py-2">
        <a class="text-decoration-none text-reset" href="https://www.linkedin.com/in/shirologic/">
            <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1 text-center">
                <img src="../../images/P8MKxO7NRG2n396LeSEs-1EMgqgjvaVvYZ7wbZ7Zm-v1.png" class="card-img-top" alt="Evan Pradipta Hardinatha">
                <div class="card-body p-0 content">
                    <p class="fs-5 fw-semibold card-title mb-1">Evan Pradipta Hardinatha</p>
                </div>
            </div>
        </a>
    </div>
    <div class="col-md-4 col-12 py-2">
        <a class="text-decoration-none text-reset" href="https://www.linkedin.com/in/jaisy-arasy/">
            <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1 text-center">
                <img src="../../images/P8MKxO7NRG2n396LeSEs-cHU7kr5izPad2OAh1eQO-v1.png" class="card-img-top" alt="Jaisy Malikulmulki Arasy">
                <div class="card-body p-0 content">
                    <p class="fs-5 fw-semibold card-title mb-1">Jaisy Malikulmulki Arasy</p>
                </div>
            </div>
        </a>
    </div>
    <div class="col-md-4 col-12 py-2">
        <a class="text-decoration-none text-reset" href="https://www.linkedin.com/in/chevhan-walidain/">
            <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1 text-center">
                <img src="../../images/P8MKxO7NRG2n396LeSEs-UTFiCKrYqaocqib3YNnZ-v1.png" class="card-img-top" alt="Chevan Walidain">
                <div class="card-body p-0 content">
                    <p class="fs-5 fw-semibold card-title mb-1">Chevan Walidain</p>
                </div>
            </div>
        </a>
    </div>
    <div class="col-md-4 col-12 py-2">
        <a class="text-decoration-none text-reset" href="https://www.linkedin.com/in/daffasyqarrr/">
            <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1 text-center">
                <img src="../../images/P8MKxO7NRG2n396LeSEs-5PupP02YXKw6a9pcZXDM-v1.png" class="card-img-top" alt="Daffa Asyqar Ahmad Khalisheka">
                <div class="card-body p-0 content">
                    <p class="fs-5 fw-semibold card-title mb-1">Daffa Asyqar Ahmad Khalisheka</p>
                </div>
            </div>
        </a>
    </div>
    <div class="col-md-4 col-12 py-2">
        <a class="text-decoration-none text-reset" href="https://www.linkedin.com/in/idham-multazam/">
            <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1 text-center">
                <img src="../../images/P8MKxO7NRG2n396LeSEs-Ra9qnq6ahPYHkvvzi71z-v1.png" class="card-img-top" alt="Idham Hanif Multazam">
                <div class="card-body p-0 content">
                    <p class="fs-5 fw-semibold card-title mb-1">Idham Hanif Multazam</p>
                </div>
            </div>
        </a>
    </div>
    <div class="col-md-4 col-12 py-2">
        <a class="text-decoration-none text-reset" href="https://www.linkedin.com/in/farrel-rassya-1b6991257/">
            <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1 text-center">
                <img src="../../images/farrel-rasya.png" class="card-img-top" alt="Farrel Rasya">
                <div class="card-body p-0 content">
                    <p class="fs-5 fw-semibold card-title mb-1">Farrel Rasya</p>
                </div>
            </div>
        </a>
    </div>
    <div class="col-md-4 col-12 py-2">
        <a class="text-decoration-none text-reset" href="http://www.linkedin.com">
            <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1 text-center">
                <img src="../../images/P8MKxO7NRG2n396LeSEs-0n0SFhW3vVnO5VXX9cIX-v1.png" class="card-img-top" alt="Razka Athallah Adnan">
                <div class="card-body p-0 content">
                    <p class="fs-5 fw-semibold card-title mb-1">Razka Athallah Adnan</p>
                </div>
            </div>
        </a>
    </div>
    <div class="col-md-4 col-12 py-2">
        <a class="text-decoration-none text-reset" href="http://linkedin.com">
            <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1 text-center">
                <img src="../../images/P8MKxO7NRG2n396LeSEs-vto2jpzeQkntjXGi2Wbu-v1.png" class="card-img-top" alt="Raffy Aulia Adnan">
                <div class="card-body p-0 content">
                    <p class="fs-5 fw-semibold card-title mb-1">Raffy Aulia Adnan</p>
                </div>
            </div>
        </a>
    </div>
</div>
