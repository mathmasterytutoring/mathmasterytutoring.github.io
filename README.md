<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Math Mastery</title>
  <!-- Tailwind CSS via CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-black text-blue-300 min-h-screen flex flex-col">
  <!-- Navigation -->
  <nav class="bg-black shadow-md">
    <div class="container mx-auto px-4 py-4 flex justify-between items-center">
      <a href="#home" class="text-2xl font-bold text-blue-400">Math Mastery</a>
      <div class="space-x-4">
        <a href="#home" class="hover:text-blue-200">Home</a>
        <a href="#about" class="hover:text-blue-200">About</a>
        <a href="#services" class="hover:text-blue-200">Services</a>
        <a href="#features" class="hover:text-blue-200">Features</a>
        <a href="#testimonials" class="hover:text-blue-200">Testimonials</a>
        <a href="#faq" class="hover:text-blue-200">FAQ</a>
        <a href="#booking" class="hover:text-blue-200">Book Now</a>
        <a href="https://docs.google.com/forms/d/1S-S_6X-x9PYrEi24YiQ4N41m142P_7IMpIGBGS2j_zU/edit" target="_blank" class="hover:text-blue-200">Contact</a>
      </div>
    </div>
  </nav>
  <main class="flex-grow">
    <!-- Hero Section -->
    <section id="home" class="container mx-auto px-4 py-16 flex flex-col md:flex-row items-center bg-blue-900 rounded-lg shadow-lg">
      <div class="md:w-1/2">
        <h1 class="text-5xl font-bold mb-6 text-blue-400">Unlock Your Math Potential</h1>
        <p class="mb-6 text-lg text-blue-200">Personalized online tutoring for Grades 1-8 to build confidence and master math.</p>
        <a href="#booking" class="inline-block px-8 py-4 bg-blue-400 text-black rounded-full hover:bg-blue-300">Book Your Session</a>
      </div>
      <div class="md:w-1/2 mt-8 md:mt-0">
        <img
        src="assets/images/Mathmastery-logo.png"
        alt="Math Mastery logo"
        class="h-10 w-auto mr-3"
      </div>
    </section>
    <!-- About Section -->
    <section id="about" class="container mx-auto px-4 py-16 bg-black rounded-lg shadow-lg mt-12">
      <h2 class="text-3xl font-bold mb-4 text-blue-400">About Me</h2>
      <p class="text-blue-200 leading-relaxed mb-4">
        Hey there! I’m <strong>Vahin Shah</strong>, a 16-year-old Ontario high school student whose passions include <strong>sports</strong> and <strong>music</strong>. I’ve been playing piano my whole life, and whether I’m on the basketball court, scoring goals in soccer, or practicing a piano sonata, I tackle every challenge with enthusiasm and creativity.
      </p>
      <p class="text-blue-200 leading-relaxed mb-4">
        I speak English, French, and Gujarati, which helps me connect with diverse students and tailor explanations in the language they’re most comfortable with.
      </p>
      <p class="text-blue-200 leading-relaxed mb-4">
        Over the past two years, I’ve maintained a consistent 90%+ in all my math courses, hold certifications in UCMAS and A+ Tutoring Programs, and continuously refine my methods based on student feedback.
      </p>
      <p class="text-blue-200 leading-relaxed">
        Beyond tutoring and music, I captain my basketball team—managing plays, mentoring new players, and leading practices—and I bring that same leadership energy into every lesson. My interactive style uses sports and musical analogies to simplify concepts, keeps sessions fast-paced, and ensures students stay engaged and confident. Ready to team up and master math? Let’s get started! 🏀🎹➗
      </p>
    </section>
    <!-- Services Section -->
    <section id="services" class="container mx-auto px-4 py-16 bg-black rounded-lg shadow-lg mt-12">
      <h2 class="text-3xl font-bold mb-8 text-blue-400">Services</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="p-6 bg-blue-800 rounded-lg shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2 text-blue-200">One-on-One Tutoring</h3>
          <p class="text-blue-200">Personalized lessons tailored to each student’s learning style and pace.</p>
        </div>
        <div class="p-6 bg-blue-800 rounded-lg shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2 text-blue-200">Group Sessions</h3>
          <p class="text-blue-200">Collaborative small groups to build teamwork skills and peer support.</p>
        </div>
        <div class="p-6 bg-blue-800 rounded-lg shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2 text-blue-200">Homework Help</h3>
          <p class="text-blue-200">Support with assignments, projects, and test prep.</p>
        </div>
      </div>
    </section>
    <!-- Features Section -->
    <section id="features" class="container mx-auto px-4 py-16 bg-black rounded-lg shadow-lg mt-12">
      <h2 class="text-3xl font-bold mb-8 text-blue-400">Why Choose Math Mastery?</h2>
      <ul class="space-y-6 text-blue-200">
        <li class="flex items-start"><span class="text-2xl text-blue-400 mr-4">✔</span><div><strong>Customized Curriculum:</strong> Lessons built around school syllabus and individual needs.</div></li>
        <li class="flex items-start"><span class="text-2xl text-blue-400 mr-4">✔</span><div><strong>Progress Tracking:</strong> Regular assessments and feedback to monitor growth.</div></li>
        <li class="flex items-start"><span class="text-2xl text-blue-400 mr-4">✔</span><div><strong>Interactive Tools:</strong> Use of digital whiteboards, quizzes, and games to reinforce concepts.</div></li>
        <li class="flex items-start"><span class="text-2xl text-blue-400 mr-4">✔</span><div><strong>Flexible Scheduling:</strong> Evening and weekend slots available to fit busy calendars.</div></li>
      </ul>
    </section>
    <!-- Testimonials Section -->
    <section id="testimonials" class="container mx-auto px-4 py-16 bg-black rounded-lg shadow-lg mt-12">
      <h2 class="text-3xl font-bold mb-8 text-blue-400">What Students Say</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="p-6 bg-blue-800 rounded-lg shadow">
          <p class="italic mb-4 text-blue-200">“Math Mastery transformed my approach to math. I went from struggling with fractions to acing my exams!”</p>
          <p class="font-semibold text-blue-200">— Sarah L., Grade 7</p>
        </div>
        <div class="p-6 bg-blue-800 rounded-lg shadow">
          <p class="italic mb-4 text-blue-200">“Vahin’s sessions are engaging and clear. My confidence has skyrocketed!”</p>
          <p class="font-semibold text-blue-200">— Jason K., Grade 5</p>
        </div>
        <div class="p-6 bg-blue-800 rounded-lg shadow">
          <p class="italic mb-4 text-blue-200">“Balancing soccer training and school was tough, but Vahin’s tutoring made math easy to understand and fit perfectly into my schedule. My grade jumped from 78% to 92% in just two months!”</p>
          <p class="font-semibold text-blue-200">— Haitham Alshbat, OPDL Soccer Athlete</p>
        </div>
      </div>
    </section>
    <!-- FAQ Section -->
    <section id="faq" class="container mx-auto px-4 py-16 bg-black rounded-lg shadow-lg mt-12">
      <h2 class="text-3xl font-bold mb-8 text-blue-400">Frequently Asked Questions</h2>
      <div class="space-y-6 text-blue-200">
        <div>
          <h3 class="font-semibold">What age/grades do you tutor?</h3>
          <p>I tutor students in Grades 1 through 8, covering foundational arithmetic, pre-algebra, and introductory geometry topics.</p>
        </div>
        <div>
          <h3 class="font-semibold">How are sessions conducted?</h3>
          <p>All sessions are online via Zoom or Google Meet, using a digital whiteboard for live problem-solving and screen sharing for interactive quizzes.</p>
        </div>
        <div>
          <h3 class="font-semibold">What is your cancellation policy?</h3>
          <p>Rescheduling or cancellations require at least 24-hour notice. Sessions canceled with less notice will be billed at 50% of the session fee to compensate planning time.</p>
        </div>
        <div>
          <h3 class="font-semibold">How do I prepare for a session?</h3>
          <p>Please have your textbook, notes, and any specific questions ready. A quiet workspace and reliable internet will help sessions run smoothly.</p>
        </div>
        <div>
          <h3 class="font-semibold">Do you offer trial sessions?</h3>
          <p>Yes! New students can book a first class free trial session to see if Math Mastery is the right fit.</p>
        </div>
      </div>
    </section>
    <<!!-- Booking Section -->
    <https://docs.google.com/forms/d/1S-S_6X-x9PYrEi24YiQ4N41m142P_7IMpIGBGS2j_zU/edit>
