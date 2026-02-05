<template>
  <div id="app">
    <!-- Navigation -->
    <nav class="nav" :class="{ 'is-scrolled': isScrolled }">
      <div class="container">
        <ul class="nav-list">
          <li><a href="#header" class="nav-link">Home</a></li>
          <li><a href="#about" class="nav-link">About</a></li>
          <li><a href="#skills" class="nav-link">Skills</a></li>
          <li><a href="#projects" class="nav-link">Projects</a></li>
          <li><a href="#contact" class="nav-link">Contact</a></li>
        </ul>
      </div>
    </nav>

    <!-- Header -->
    <header id="header" class="header">
      <div class="container">
        <div class="header-content">
          <img src="/images/star.jpg" alt="Esther Kemigisha" class="profile-img">
          <div class="header-text">
            <p style="font-size: 1.2rem; margin-bottom: 0.5rem; opacity: 0.9;">Hello I'm,</p>
            <h1>Esther Kemigisha</h1>
            <h2>Full Stack Developer & UI/UX Designer</h2>
            <div class="summary-text">
              <p>Passionate Developer creating intuitive user interfaces .</p>
              <p>Building scalable full-stack applications that deliver seamless user experiences, driven by clean UI and performance optimization.</p>
             
            </div>
          </div>
        </div>
      </div>
    </header>

    <!-- About Section -->
    <section id="about" class="section animate-on-scroll">
      <div class="container">
        <h2 class="section-title animate-on-scroll">About Me</h2>
        <div class="about-wrapper animate-on-scroll">
          <div class="about-content">
            <p>I'm a passionate Developer focused on creating intuitive and responsive user interfaces.</p>
            <p>I build scalable full-stack applications that deliver seamless user experiences. Driven by clean UI, usability, and performance optimization. Continuously learning and evolving with the latest technologies.</p>
            <p>In addition to web development, I bring strong graphic design skills that help create visually appealing and cohesive user experiences. My expertise includes:</p>
            <ul>
              <li>Seamlessly integrating visuals with frontend code for polished, brand-consistent results</li>
            </ul>
            <p>Combining frontend development and my backend ensures my applications are both visually striking and highly functional.</p>
          </div>
          <img src="/images/star.jpg" alt="Esther Kemigisha" class="about-img">
        </div>
      </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="section animate-on-scroll">
      <div class="container">
        <h2 class="section-title animate-on-scroll">My Skills</h2>
        <div class="skills-grid">
          <div class="skill-category animate-on-scroll">
            <h3>Technical Skills</h3>
            <div class="skill-items">
              <div class="skill-item animate-on-scroll">
                <i class="fab fa-html5"></i>
                <p>HTML5</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fab fa-css3-alt"></i>
                <p>CSS3</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fab fa-js-square"></i>
                <p>JavaScript</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fab fa-vuejs"></i>
                <p>Vue.js</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fab fa-react"></i>
                <p>React</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fab fa-node-js"></i>
                <p>Node.js</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fas fa-database"></i>
                <p>MongoDB</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fab fa-git-alt"></i>
                <p>Git</p>
              </div>
            </div>
          </div>
          
          <div class="skill-category animate-on-scroll">
            <h3>Soft Skills</h3>
            <div class="skill-items">
              <div class="skill-item animate-on-scroll">
                <i class="fas fa-comments"></i>
                <p>Communication</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fas fa-users"></i>
                <p>Teamwork</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fas fa-lightbulb"></i>
                <p>Problem-Solving</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fas fa-clock"></i>
                <p>Time Management</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fas fa-sync-alt"></i>
                <p>Adaptability</p>
              </div>
              <div class="skill-item animate-on-scroll">
                <i class="fas fa-handshake"></i>
                <p>Collaboration</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section animate-on-scroll">
      <div class="container">
        <h2 class="section-title animate-on-scroll">Featured Projects</h2>
        <div class="projects-grid">
          <div class="project-card animate-on-scroll">
            <img src="/images/image.png" alt="SwanAir Safaris" class="project-img">
            <div class="project-content">
              <h3 class="project-title">SwanAir Safaris & Travel</h3>
              <p>Comprehensive costing software for safari and travel management with automated pricing and booking systems.</p>
            </div>
          </div>
          
          <div class="project-card animate-on-scroll">
            <img src="/images/Grocery.png" alt="KGL Inventory" class="project-img">
            <div class="project-content">
              <h3 class="project-title">KGL-Inventory Management System</h3>
              <p>Full-stack web application for managing procurement, sales, and credit operations in wholesale produce business.</p>
            </div>
          </div>
          
          <div class="project-card animate-on-scroll">
            <img src="/images/Jewelry.png" alt="KHOHAV Jewelry" class="project-img">
            <div class="project-content">
              <h3 class="project-title">KHOHAV – Jewelry E-commerce</h3>
              <p>Modern e-commerce frontend for elegant and timeless jewelry brand with seamless shopping experience.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section animate-on-scroll">
      <div class="container">
        <h2 class="section-title animate-on-scroll">Hire Me</h2>
        <div class="contact-wrapper">
          <div class="contact-content animate-on-scroll">
            <p>You can reach me directly via email or connect with me on the platforms below:</p>
            
            <div class="contact-info">
              <div class="contact-item-plain animate-on-scroll">
                <i class="fas fa-envelope"></i>
                <span>estarkemi@gmail.com</span>
              </div>
              
              <div class="contact-item-plain animate-on-scroll">
                <i class="fas fa-phone"></i>
                <span>+257-788-345-329</span>
              </div>
              
              <div class="contact-item-plain animate-on-scroll">
                <i class="fas fa-map-marker-alt"></i>
                <span>Kampala</span>
              </div>
            </div>
            
            <div class="social-links animate-on-scroll">
              <a href="https://linkedin.com/in/esther-kemigisha" class="social-link" target="_blank">
                <i class="fab fa-linkedin-in"></i>
              </a>
              <a href="https://github.com/esther-kemigisha" class="social-link" target="_blank">
                <i class="fab fa-github"></i>
              </a>
            </div>
          </div>
          
          <div class="contact-form animate-on-scroll">
            <form>
              <input type="text" placeholder="Your Full Name" required>
              <input type="email" placeholder="Your Email" required>
              <div class="phone-input">
                <select class="country-code" required>
                  <option value="+256">🇺🇬 +256</option>
                  <option value="+1">🇺🇸 +1</option>
                  <option value="+44">🇬🇧 +44</option>
                  <option value="+254">🇰🇪 +254</option>
                  <option value="+255">🇹🇿 +255</option>
                  <option value="+250">🇷🇼 +250</option>
                  <option value="+257">🇧🇮 +257</option>
                  <option value="+27">🇿🇦 +27</option>
                  <option value="+234">🇳🇬 +234</option>
                  <option value="+233">🇬🇭 +233</option>
                </select>
                <input type="tel" placeholder="Phone Number" required>
              </div>
              <textarea placeholder="Your Message" rows="4" required></textarea>
              <button type="submit">Send Message</button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <div class="container">
        <p>&copy; 2026 Esther Kemigisha. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      isScrolled: false
    }
  },
  mounted() {
    this.observeElements()
    window.addEventListener('scroll', this.handleScroll)
  },
  beforeUnmount() {
    window.removeEventListener('scroll', this.handleScroll)
  },
  methods: {
    handleScroll() {
      this.isScrolled = window.scrollY > 50
    },
    observeElements() {
      const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            entry.target.classList.add('animate-in')
          }
        })
      }, {
        threshold: 0.1,
        rootMargin: '0px 0px -50px 0px'
      })

      document.querySelectorAll('.animate-on-scroll').forEach(el => {
        observer.observe(el)
      })
    }
  }
}
</script>