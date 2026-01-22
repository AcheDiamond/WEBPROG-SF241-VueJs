<template>
  <div class="pp-root">
    <!-- Navbar -->
    <nav id="siteNav" class="navbar navbar-expand-lg navbar-light sticky-top nav-glass border-bottom">
      <div class="container">
        <a class="navbar-brand fw-bold" href="#home">Amiel</a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navLinks"
                aria-controls="navLinks" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navLinks">
          <ul class="navbar-nav ms-auto gap-lg-2">
            <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
            <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
            <li class="nav-item"><a class="nav-link" href="#education">Education</a></li>
            <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
            <li class="nav-item"><a class="nav-link" href="#hobbies">Hobbies</a></li>
            <li class="nav-item"><a class="nav-link" href="#goals">Goals</a></li>
            <li class="nav-item"><a class="btn btn-sm btn-primary ms-lg-2" href="#contact">Contact</a></li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Hero -->
    <header id="home" class="hero-section">
      <div class="container py-5">
        <div class="row align-items-center gy-4">
          <div class="col-lg-7 text-center text-lg-start">
            <p class="subtitle mb-2">WEBPROG SF241 • Personal Website</p>

            <h1 class="display-4 fw-bold mb-2 hero-title">
              <span class="hero-muted">Hi, my name is</span>
              <span class="hero-name">Amiel</span>.
            </h1>

            <p class="lead mb-4">
              <span class="hero-muted">I’m a </span>
              <span id="typingText" class="typing"></span>
              <span class="typing-cursor" aria-hidden="true">|</span>
            </p>

            <div class="d-flex flex-wrap gap-2 justify-content-center justify-content-lg-start">
              <a class="btn btn-primary btn-lg" href="#about">Explore</a>
              <a class="btn btn-outline-primary btn-lg" href="#skills">My Skills</a>
            </div>

            <p class="scroll-hint mb-0 mt-4">Scroll to explore ↓</p>
          </div>

          <div class="col-lg-5">
            <div class="profile-card">
              <span class="card-badge">Profile</span>
              <h2 class="h4 mb-3">Quick Intro</h2>

              <div class="quick-grid">
                <div class="quick-chip"><strong>Nickname:</strong> <span class="text-muted">Miel / AD</span></div>
                <div class="quick-chip"><strong>Track:</strong> <span class="text-muted">Cybersecurity & Forensics</span></div>
                <div class="quick-chip"><strong>Tools:</strong> <span class="text-muted">Java, Python, Ubuntu</span></div>
                <div class="quick-chip"><strong>Goal:</strong> <span class="text-muted">Feel Alive Again</span></div>
              </div>

              <div class="profile-img-container">
                <img
                  src="/assets/img/profile-picture.jpg"
                  alt="Portrait of Amiel Chavez"
                  class="profile-img"
                  width="420"
                  height="520"
                  loading="lazy"
                />
                <p class="small text-muted mt-2 mb-0">As you can see, I like the color blue.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>

    <main>
      <!-- About -->
      <section id="about" class="content-section">
        <div class="container">
          <div class="section-header">
            <h2 class="section-title">About Me</h2>
          </div>

          <div class="row g-4">
            <div class="col-lg-7">
              <div class="profile-card h-100">
                <span class="card-badge">About</span>
                <h3 class="h5">Who I am</h3>
                <p>
                  Hello! I’m Amiel Chavez, a Computer Science student specializing in
                  <span class="highlight">Cybersecurity & Forensics</span>.
                  I enjoy staying at home, or sometimes go outside by myself and appreciate nature.
                </p>
                <p class="mb-0">
                  I love <span class="highlight">Playing Online Games, Cats & Dogs, Coffee and Pastries</span>,
                  <span class="highlight">Sleeping</span>, and <span class="highlight">Sunsets</span>!
                </p>
              </div>
            </div>

            <div class="col-lg-5">
              <div class="profile-card h-100">
                <span class="card-badge">Focus</span>
                <h3 class="h5">What I’m working on</h3>
                <ul class="mb-0">
                  <li>Working out to build a bit of strength and muscles</li>
                  <li>Learn and understand myself better</li>
                  <li>Finding things I enjoy so I can feel alive</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Education -->
      <section id="education" class="content-section section-alt">
        <div class="container">
          <div class="section-header">
            <h2 class="section-title">Education</h2>
            <p class="section-subtitle">Me currently.</p>
          </div>

          <div class="row g-4">
            <div class="col-md-6">
              <div class="profile-card h-100">
                <span class="card-badge">School</span>
                <h3 class="h5">Asia Pacific College</h3>
                <p class="mb-0">
                  <strong>Program:</strong> BS Computer Science<br>
                  <strong>Section:</strong> SF241
                </p>
              </div>
            </div>

            <div class="col-md-6">
              <div class="profile-card h-100">
                <span class="card-badge">Course</span>
                <h3 class="h5">WEBPROG</h3>
                <p class="mb-0">In this course, we are currently trying to build our Personal Web(this).</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Skills -->
      <section id="skills" class="content-section">
        <div class="container">
          <div class="section-header">
            <h2 class="section-title">Skills</h2>
            <p class="section-subtitle">This section shows programming skills I know a bit (i am very lacking).</p>
          </div>

          <div class="skills-grid">
            <div class="skill-tile">HTML</div>
            <div class="skill-tile">Arduino</div>
            <div class="skill-tile">JavaScript</div>
            <div class="skill-tile">CSS</div>
            <div class="skill-tile">Kali</div>
            <div class="skill-tile">Java</div>
            <div class="skill-tile">Python</div>
            <div class="skill-tile">Ubuntu</div>
          </div>
        </div>
      </section>

      <!-- Hobbies -->
      <section id="hobbies" class="content-section section-alt hobbies-bg">
        <div class="container">
          <div class="section-header">
            <h2 class="section-title">Hobbies & Interests</h2>
            <p class="section-subtitle">Things I enjoy nowadays.</p>
          </div>

          <div class="profile-card">
            <span class="card-badge">Fun</span>
            <div class="row g-3">
              <div class="col-md-6">
                <ul class="mb-0">
                  <li>Movies</li>
                  <li>Music</li>
                  <li>Online games</li>
                  <li>Video games</li>
                  <li>Billiards</li>
                </ul>
              </div>
              <div class="col-md-6">
                <ul class="mb-0">
                  <li>Photography</li>
                  <li>Art gallery</li>
                  <li>Manhwa</li>
                  <li>Anime</li>
                </ul>
              </div>
            </div>
          </div>

          <!-- Gallery Carousel -->
          <div class="profile-card mt-4">
            <GalleryCarousel />
            <p class="small text-muted mt-2 mb-0">Swipe on mobile or use arrows on desktop.</p>
          </div>
        </div>
      </section>

      <!-- Goals -->
      <section id="goals" class="content-section">
        <div class="container">
          <div class="section-header">
            <h2 class="section-title">Goals</h2>
            <p class="section-subtitle">Clear and simple.</p>
          </div>

          <div class="profile-card">
            <span class="card-badge">Goals</span>
            <p class="mb-0">
              I want to travel, understand more about all things, and build a comfortable future.
              One day, I’d also love to own a <span class="highlight">Bugatti Chiron Pur Sport</span>.
            </p>
          </div>
        </div>
      </section>

      <!-- Contact -->
      <section id="contact" class="content-section section-alt">
        <div class="container">
          <div class="section-header">
            <h2 class="section-title">Contact</h2>
            <p class="section-subtitle">Client-side validation + copy email feature.</p>
          </div>

          <div class="row g-4">
            <div class="col-lg-6">
              <form class="profile-card" id="contactForm" novalidate @submit.prevent="handleSubmit">
                <span class="card-badge">Message</span>

                <div class="mb-3">
                  <label for="name" class="form-label">Name</label>
                  <input id="name" class="form-control" type="text" v-model.trim="form.name" required>
                  <div class="invalid-feedback">Please enter your name.</div>
                </div>

                <div class="mb-3">
                  <label for="email" class="form-label">Email</label>
                  <input id="email" class="form-control" type="email" v-model.trim="form.email" required>
                  <div class="invalid-feedback">Please enter a valid email.</div>
                </div>

                <div class="mb-3">
                  <label for="message" class="form-label">Message</label>
                  <textarea id="message" class="form-control" rows="4" v-model.trim="form.message" required></textarea>
                  <div class="invalid-feedback">Please enter a message.</div>
                </div>

                <div class="d-flex flex-wrap gap-2">
                  <button class="btn btn-primary" type="submit">Send (demo)</button>
                  <button class="btn btn-outline-primary" type="button" @click="copyEmail">Copy my email</button>
                </div>

                <p class="small mt-3 mb-0" id="formStatus" role="status" aria-live="polite">{{ statusText }}</p>
                <p class="small text-muted mt-2 mb-0">
                  Email: <span id="myEmail">{{ myEmail }}</span> <span class="text-muted">(dont spam pls)</span>
                </p>

                <!-- Guestbook feed -->
                <ContactGuestbookFeed class="mt-3" :entries="entries" />
              </form>
            </div>

            <div class="col-lg-6">
              <div class="profile-card h-100 links-card">
                <span class="card-badge">Links</span>

                <a class="refs-sticker" href="/resources.html" aria-label="Open Resources and References page">
                  <img src="/assets/img/AD-Smol.png" alt="Click me for references">
                </a>

                <div class="copy-toast" id="copyToast" role="status" aria-live="polite"></div>

                <h3 class="h5 mb-3">Find me online</h3>

                <ul class="social-list">
                  <li class="social-item">
                    <div class="social-left">
                      <span class="social-icon" aria-hidden="true">🐙</span>
                      <a class="social-link" href="https://github.com/AcheDiamond" target="_blank" rel="noopener">GitHub</a>
                      <span class="social-handle">AcheDiamond</span>
                    </div>
                    <button class="btn btn-outline-primary copy-btn" type="button" @click="copyText('AcheDiamond')">Copy</button>
                  </li>

                  <li class="social-item">
                    <div class="social-left">
                      <span class="social-icon" aria-hidden="true">💼</span>
                      <a class="social-link" href="https://www.linkedin.com/in/amiel-chavez-b58154343/" target="_blank" rel="noopener">LinkedIn</a>
                      <span class="social-handle">amiel-chavez</span>
                    </div>
                    <button class="btn btn-outline-primary copy-btn" type="button" @click="copyText('amiel-chavez')">Copy</button>
                  </li>

                  <li class="social-item">
                    <div class="social-left">
                      <span class="social-icon" aria-hidden="true">📘</span>
                      <a class="social-link" href="https://www.facebook.com/amiel.chavez.583" target="_blank" rel="noopener">Facebook</a>
                      <span class="social-handle">amiel.chavez.583</span>
                    </div>
                    <button class="btn btn-outline-primary copy-btn" type="button" @click="copyText('amiel.chavez.583')">Copy</button>
                  </li>

                  <li class="social-item">
                    <div class="social-left">
                      <span class="social-icon" aria-hidden="true">📷</span>
                      <a class="social-link" href="https://www.instagram.com/he_was.once/" target="_blank" rel="noopener">Instagram</a>
                      <span class="social-handle">@he_was.once</span>
                    </div>
                    <button class="btn btn-outline-primary copy-btn" type="button" @click="copyText('@he_was.once')">Copy</button>
                  </li>
                </ul>

                <p class="text-muted mt-3 mb-0">
                  Tip: click the sticker to view the references/resources used.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer class="py-4 border-top footer-soft">
      <div class="container d-flex flex-column flex-md-row justify-content-between align-items-center gap-2">
        <small class="text-muted">© <span id="year">{{ year }}</span> Amiel Chavez • WEBPROG SF241</small>
        <small class="text-muted">Single-page responsive site (Bootstrap 5 + CSS Grid/Flex + JS)</small>
      </div>
    </footer>
  </div>
</template>

<script setup>
import { computed, onMounted, reactive, ref } from "vue";

import "./personalprofile.css";

onMounted(() => {

  year.value = new Date().getFullYear();

  const typingEl = document.getElementById("typingText");
  const words = ["Chopped Asian boi", "Computer Science Student", "Blue Lover"];

  let wi = 0;
  let ci = 0;
  let deleting = false;

  const typingSpeed = 70;
  const deletingSpeed = 45;
  const pauseAfterType = 1100;
  const pauseAfterDelete = 350;

  function typeLoop() {
    if (!typingEl) return;
    const word = words[wi];

    if (!deleting) {
      typingEl.textContent = word.slice(0, ci + 1);
      ci++;

      if (ci < word.length) setTimeout(typeLoop, typingSpeed);
      else {
        setTimeout(() => {
          deleting = true;
          typeLoop();
        }, pauseAfterType);
      }
    } else {
      typingEl.textContent = word.slice(0, ci - 1);
      ci--;

      if (ci > 0) setTimeout(typeLoop, deletingSpeed);
      else {
        deleting = false;
        wi = (wi + 1) % words.length;
        setTimeout(typeLoop, pauseAfterDelete);
      }
    }
  }
  typeLoop();

  const nav = document.getElementById("siteNav");
  const navH = nav ? nav.offsetHeight : 0;
  const OFFSET = navH + 40;
  document.documentElement.style.scrollPaddingTop = `${OFFSET}px`;

  const navLinks = document.querySelectorAll('#siteNav a[href^="#"]');
  navLinks.forEach((a) => {
    a.addEventListener("click", (e) => {
      const href = a.getAttribute("href");
      if (!href || href === "#") return;

      const target = document.querySelector(href);
      if (!target) return;

      e.preventDefault();
      const y = target.getBoundingClientRect().top + window.pageYOffset - OFFSET;
      window.scrollTo({ top: y, behavior: "smooth" });
    });
  });
});

const myEmail = "chavez.amiel.diamond@gmail.com";
const statusText = ref("");
const year = ref(new Date().getFullYear());

const form = reactive({ name: "", email: "", message: "" });
const entries = ref([]);

function loadEntries() {
  const saved = localStorage.getItem("guestbookEntries");
  entries.value = saved ? JSON.parse(saved) : [];
}
loadEntries();

function saveEntry(entry) {
  const saved = localStorage.getItem("guestbookEntries");
  const arr = saved ? JSON.parse(saved) : [];
  arr.unshift(entry);
  localStorage.setItem("guestbookEntries", JSON.stringify(arr));
  loadEntries();
}

function handleSubmit(e) {
  const formEl = document.getElementById("contactForm");
  if (!formEl) return;

  if (!formEl.checkValidity()) {
    formEl.classList.add("was-validated");
    statusText.value = "Please fix the errors above.";
    return;
  }

  saveEntry({
    name: form.name,
    email: form.email,
    message: form.message,
    time: new Date().toLocaleString(),
  });

  statusText.value = "Message sent (demo). Thank you!";
  form.name = "";
  form.email = "";
  form.message = "";
  formEl.classList.remove("was-validated");
}

function showToast(text) {
  const toast = document.getElementById("copyToast");
  if (!toast) return;
  toast.textContent = text;
  toast.classList.add("show");
  setTimeout(() => toast.classList.remove("show"), 1200);
}

async function copyText(value) {
  const v = (value || "").trim();
  if (!v) return;

  try {
    if (navigator.clipboard?.writeText) {
      await navigator.clipboard.writeText(v);
      showToast("Copied!");
      return;
    }
  } catch {}

  const ta = document.createElement("textarea");
  ta.value = v;
  ta.setAttribute("readonly", "");
  ta.style.position = "fixed";
  ta.style.top = "-9999px";
  document.body.appendChild(ta);
  ta.select();

  try {
    document.execCommand("copy");
    showToast("Copied!");
  } catch {
    showToast("Copy failed");
  } finally {
    document.body.removeChild(ta);
  }
}

function copyEmail() {
  statusText.value = "";
  copyText(myEmail);
}

const GalleryCarousel = {
  name: "GalleryCarousel",
  setup() {
    const index = ref(0);
    const xStart = ref(0);
    const xEnd = ref(0);
    const orientationMap = reactive({});

    const images = Array.from({ length: 16 }, (_, i) => `/assets/img/gallery/${i + 1}.png`);

    const currentSrc = computed(() => images[index.value]);

    const frameClass = computed(() => {
      const o = orientationMap[currentSrc.value] || "landscape";
      return {
        "is-portrait": o === "portrait",
        "is-landscape": o === "landscape",
        "is-square": o === "square",
      };
    });

    function next() {
      index.value = (index.value + 1) % images.length;
    }
    function prev() {
      index.value = (index.value - 1 + images.length) % images.length;
    }
    function goTo(i) {
      index.value = i;
    }

    function touchStart(e) {
      xStart.value = e.changedTouches[0].screenX;
    }
    function touchEnd(e) {
      xEnd.value = e.changedTouches[0].screenX;
      const diff = xStart.value - xEnd.value;
      if (Math.abs(diff) < 30) return;
      if (diff > 0) next();
      else prev();
    }

    function onImgLoad(e) {
      const img = e.target;
      const w = img.naturalWidth || 0;
      const h = img.naturalHeight || 0;
      if (!w || !h) return;

      let o = "landscape";
      if (h > w * 1.05) o = "portrait";
      else if (w > h * 1.05) o = "landscape";
      else o = "square";

      orientationMap[currentSrc.value] = o;
    }

    return { index, images, currentSrc, frameClass, next, prev, goTo, touchStart, touchEnd, onImgLoad };
  },
  template: `
    <div>
      <span class="card-badge">Gallery</span>
      <h3 class="h5 mb-3">Hobbies Photo Gallery</h3>

      <div class="carousel-wrap" @touchstart="touchStart" @touchend="touchEnd">
        <button class="carousel-btn" type="button" @click="prev" aria-label="Previous">‹</button>

        <div class="carousel-frame" :class="frameClass">
          <img
            :src="currentSrc"
            class="gallery-img"
            :alt="'Hobby photo ' + (index + 1)"
            @load="onImgLoad"
          />
        </div>

        <button class="carousel-btn" type="button" @click="next" aria-label="Next">›</button>
      </div>

      <div class="carousel-dots" aria-label="Gallery dots">
        <span v-for="n in images.length"
              :key="n"
              class="dot"
              :class="{active:(n-1)===index}"
              @click="goTo(n-1)"></span>
      </div>
    </div>
  `,
};

const ContactGuestbookFeed = {
  name: "ContactGuestbookFeed",
  props: { entries: { type: Array, required: true } },
  template: `
    <div class="mt-4">
      <h4 class="h6 mb-3">Messages</h4>

      <div v-if="entries.length === 0" class="text-muted small">
        No messages yet.
      </div>

      <div v-for="(e, i) in entries" :key="i" class="guest-entry">
        <div class="d-flex align-items-baseline gap-2 flex-wrap">
          <strong>{{ e.name }}</strong>
          <span v-if="e.email" class="text-muted small">({{ e.email }})</span>
          <span class="text-muted small">• {{ e.time }}</span>
        </div>
        <p class="mb-0">{{ e.message }}</p>
      </div>
    </div>
  `,
};
</script>

<style></style>
