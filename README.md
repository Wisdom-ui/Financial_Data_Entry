<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>

<body class="bg-gray-50 text-gray-800">
  <!-- Header -->
  <header class="bg-white shadow-md sticky top-0 z-10">
    <div class="max-w-5xl mx-auto px-6 py-4 flex items-center justify-between">
      <h1 class="text-2xl font-bold text-blue-700">Wisdom Nwosu</h1>
      <nav class="space-x-6 text-gray-600 font-medium">
        <a href="#about" class="hover:text-blue-700">About</a>
        <a href="#skills" class="hover:text-blue-700">Skills</a>
        <a href="#projects" class="hover:text-blue-700">Projects</a>
        <a href="#contact" class="hover:text-blue-700">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="hero" class="bg-blue-700 text-white py-20">
    <div class="max-w-4xl mx-auto flex flex-col items-center text-center px-4">
      <img src="profile.jpg" alt="Wisdom Nwosu" class="w-40 h-40 rounded-full shadow-lg border-4 border-white mb-6 object-cover">
      <h2 class="text-4xl font-bold mb-2">Wisdom Nwosu</h2>
      <p class="text-xl">Empowering Data Accuracy through Technology</p>
      <div class="mt-4 flex space-x-4">
        <a href="mailto:wisdomchinwosu@gmail.com" class="bg-white text-blue-700 px-4 py-2 rounded-lg font-semibold hover:bg-gray-100">Email Me</a>
        <a href="https://www.linkedin.com/in/wisdom-nwosu" target="_blank" class="bg-blue-900 text-white px-4 py-2 rounded-lg font-semibold hover:bg-blue-800">LinkedIn</a>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="max-w-5xl mx-auto py-16 px-6">
    <h3 class="text-3xl font-bold text-blue-700 mb-4">About Me</h3>
    <p class="text-lg leading-relaxed">
      I am a meticulous and analytical Data Specialist with a strong foundation in financial data management.
      Proficient in QuickBooks Online, data reconciliation, and process improvement, I bring exceptional attention to detail
      and a problem-solving mindset that enhances data accuracy and operational efficiency. I aim to apply my technical and
      analytical skills to support organizational missions in a remote, collaborative environment.
    </p>
  </section>

  <!-- Skills -->
  <section id="skills" class="bg-gray-100 py-16">
    <div class="max-w-5xl mx-auto px-6">
      <h3 class="text-3xl font-bold text-blue-700 mb-6">Skills & Certifications</h3>
      <div class="grid grid-cols-2 md:grid-cols-3 gap-6 text-center">
        <div class="bg-white p-4 rounded-lg shadow">QuickBooks Online</div>
        <div class="bg-white p-4 rounded-lg shadow">Excel Certified</div>
        <div class="bg-white p-4 rounded-lg shadow">Technical Support Engineer</div>
        <div class="bg-white p-4 rounded-lg shadow">Data Entry & Reconciliation</div>
        <div class="bg-white p-4 rounded-lg shadow">Accounting & Bookkeeping</div>
        <div class="bg-white p-4 rounded-lg shadow">Process Improvement</div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="max-w-5xl mx-auto py-16 px-6">
    <h3 class="text-3xl font-bold text-blue-700 mb-6">Projects & Achievements</h3>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="bg-white shadow-lg rounded-lg p-6">
        <h4 class="text-xl font-semibold mb-2">Financial Data Dashboard (Excel)</h4>
        <p class="text-gray-600">
          Built a dynamic financial data dashboard using Excel formulas and pivot tables,
          improving reporting efficiency by <strong>25%</strong> and providing real-time insights for budget tracking.
        </p>
      </div>
      <div class="bg-white shadow-lg rounded-lg p-6">
        <h4 class="text-xl font-semibold mb-2">QuickBooks Reconciliation Automation</h4>
        <p class="text-gray-600">
          Automated bank reconciliation workflows in QuickBooks Online, increasing accuracy by <strong>30%</strong>
          and cutting reconciliation time from 4 hours to under 1 hour per session.
        </p>
      </div>
      <div class="bg-white shadow-lg rounded-lg p-6">
        <h4 class="text-xl font-semibold mb-2">Data Entry Accuracy Enhancement</h4>
        <p class="text-gray-600">
          Designed and implemented a verification and reconciliation framework that boosted overall data entry
          accuracy to <strong>99.5%</strong> across multiple datasets, ensuring data consistency and integrity.
        </p>
      </div>
      <div class="bg-white shadow-lg rounded-lg p-6">
        <h4 class="text-xl font-semibold mb-2">Accounting Workflow Optimization</h4>
        <p class="text-gray-600">
          Optimized bookkeeping and accounting workflows for a small business client, reducing monthly closing time
          by <strong>35%</strong> and improving financial record transparency.
        </p>
      </div>
      <div class="bg-white shadow-lg rounded-lg p-6">
        <h4 class="text-xl font-semibold mb-2">Process Improvement Tracker</h4>
        <p class="text-gray-600">
          Developed a process improvement tracking system for data entry performance that reduced human errors by
          <strong>18%</strong> and improved completion rates by <strong>15%</strong>.
        </p>
      </div>
      <div class="bg-white shadow-lg rounded-lg p-6">
        <h4 class="text-xl font-semibold mb-2">Financial Reporting Automation</h4>
        <p class="text-gray-600">
          Created automated reporting templates that integrated QuickBooks data into Excel for consolidated
          financial summaries, cutting manual data processing by <strong>40%</strong>.
        </p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="bg-blue-700 text-white py-16">
    <div class="max-w-4xl mx-auto px-6 text-center">
      <h3 class="text-3xl font-bold mb-4">Get in Touch</h3>
      <p class="mb-6">Let's collaborate or discuss opportunities. Fill the form below and I'll respond promptly.</p>
      <form action="https://formspree.io/f/mwpeqwgo" method="POST" class="max-w-md mx-auto space-y-4">
        <input type="text" name="name" placeholder="Your Name" required class="w-full p-3 rounded text-gray-800">
        <input type="email" name="email" placeholder="Your Email" required class="w-full p-3 rounded text-gray-800">
        <textarea name="message" placeholder="Your Message" rows="4" required class="w-full p-3 rounded text-gray-800"></textarea>
        <button type="submit" class="bg-white text-blue-700 font-semibold px-6 py-2 rounded-lg hover:bg-gray-200">Send Message</button>
      </form>
    </div>
  </section>

  <footer class="text-center py-6 text-gray-600 text-sm bg-white">
    &copy; 2025 Wisdom Nwosu. All rights reserved.
  </footer>
</body>
</html>
