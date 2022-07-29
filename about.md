---
layout: article
titles:
  # @start locale config
  en      : &EN       About
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
  zh-Hans : &ZH_HANS  关于
  zh      : *ZH_HANS
  zh-CN   : *ZH_HANS
  zh-SG   : *ZH_HANS
  zh-Hant : &ZH_HANT  關於
  zh-TW   : *ZH_HANT
  zh-HK   : *ZH_HANT
  ko      : &KO       소개
  ko-KR   : *KO
  fr      : &FR       À propos
  fr-BE   : *FR
  fr-CA   : *FR
  fr-CH   : *FR
  fr-FR   : *FR
  fr-LU   : *FR
  # @end locale config
key: page-about
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" />
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tw-elements/dist/css/index.min.css" />
<script src="https://cdn.tailwindcss.com"></script>
<script>
  tailwind.config = {
    theme: {
      extend: {
        fontFamily: {
          sans: ['Inter', 'sans-serif'],
        },
      }
    }
  }
</script>
<script src="https://cdn.jsdelivr.net/npm/tw-elements/dist/js/index.min.js"></script>

<!-- <script src="https://cdn.tailwindcss.com"></script> -->

<div
  class="p-12 text-center relative overflow-hidden bg-no-repeat bg-cover rounded-lg"
  style="
    background-image: url('https://user-images.githubusercontent.com/19698023/181514172-2568fc26-1711-47e0-b7d0-260f190e8834.jpeg');
    height: 400px;
  ">
  <div
    class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed"
    style="background-color: rgba(0, 0, 0, 0.6)">
    <div class="flex justify-center items-center h-full">
      <div class="text-white">
        <h2 class="font-semibold text-4xl mb-4" style="color: white">EDIT ML Intern Summer Projects</h2>
        <h4 class="font-semibold text-xl mb-6" style="color: white">Program Information</h4>
        <a
          class="inline-block px-7 py-3 mb-1 border-2 border-gray-200 text-gray-200 font-medium text-sm leading-snug uppercase rounded hover:bg-black hover:bg-opacity-5 focus:outline-none focus:ring-0 transition duration-150 ease-in-out"
          href="/EDIT_AI_virtual_conference/presenters"
          role="button"
          data-mdb-ripple="true"
          data-mdb-ripple-color="light">Listen to our presenters</a>
      </div>
    </div>
  </div>
</div>

<br>
<div class="grid grid-cols-2 gap-4">
  <div class="accordion" id="accordionExample">
    <div class="accordion-item bg-white border border-gray-200">
      <h2 class="accordion-header mb-0" id="headingOne">
        <button class="
          accordion-button
          relative
          flex
          items-center
          w-full
          py-4
          px-5
          text-base text-gray-800 text-left
          bg-white
          border-0
          rounded-none
          transition
          focus:outline-none
        " type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true"
          aria-controls="collapseOne">
          What is the EDIT ML Summer Internship program?
        </button>
      </h2>
      <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne"
        data-bs-parent="#accordionExample">
        <div class="accordion-body py-4 px-5">
        The <a href="https://levylab.host.dartmouth.edu/"><strong>Emerging Diagnostic and Investigative Technologies (EDIT)</strong> Machine Learning program</a> is an integrated and collaborative resource spanning across multiple clinical departments and is focused on developing innovative diagnostic AI technologies.

        Interns will learn to develop and apply artificial intelligence technologies in medicine with an emphasis on cancer translational sciences. Program components will include: 1) didactics with lectures, online tutorials, and workshop classes featuring a biomedical curriculum covering key biomedical and artificial intelligence concepts; 2) guided research projects with emphasis on building research independence, and 3) supported basic lab research. Students will work as members of existing labs to develop algorithms across the range of diagnostic methods in pathology and other clinical subspecialties, from cancer detection and gigapixel image manipulation to text prediction, amongst others.  Students will be mentored by biomedical researchers and clinicians from the departments of Pathology, Dermatology, Radiation Oncology, Quantitative Biomedical Sciences, Epidemiology and Biomedical Data Science.  

        Through participation in the summer internship program, interns will learn to design and pitch projects, to use and develop open-source, reproducible biomedical informatics software, and to work in a team culture which promotes broad collaboration.
        </div>
      </div>
    </div>
    <div class="accordion-item bg-white border border-gray-200">
      <h2 class="accordion-header mb-0" id="headingTwo">
        <button class="
          accordion-button
          collapsed
          relative
          flex
          items-center
          w-full
          py-4
          px-5
          text-base text-gray-800 text-left
          bg-white
          border-0
          rounded-none
          transition
          focus:outline-none
        " type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false"
          aria-controls="collapseTwo">
          What will students learn about in the EDIT ML program?
        </button>
      </h2>
      <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo"
        data-bs-parent="#accordionExample">
        <div class="accordion-body py-4 px-5">
        Students will <strong>learn about</strong>:
          <ul class="list-decimal">
            <li>Medical subspecialties and current biomedical challenges</li>
            <li>Computer programming, statistics and artificial intelligence technologies</li>
            <li>Potential application of AI technologies to clinical practice</li>
            <li>High performance computing</li>
            <li>Professional development skills, i.e., prepare presentations, write manuscripts, scientific research process.</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="accordion-item bg-white border border-gray-200">
      <h2 class="accordion-header mb-0" id="headingThree">
        <button class="
          accordion-button
          collapsed
          relative
          flex
          items-center
          w-full
          py-4
          px-5
          text-base text-gray-800 text-left
          bg-white
          border-0
          rounded-none
          transition
          focus:outline-none
        " type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false"
          aria-controls="collapseThree">
          Information on program tracks:
        </button>
      </h2>
      <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree"
        data-bs-parent="#accordionExample">
        <div class="accordion-body py-4 px-5">
        Students are placed into <strong>one of three tracks</strong>:
          <ul class="list-decimal">
            <li>Skills Development Track: for students who are learning or have learned basic programming skills and/or are interested in computational projects with medical applications. These students will work through learning modules and complete mini-projects for their summer experience. The emphasis is for the student to learn more about biomedical research and build advanced programming skills. Students may have the option to work on supervised research projects.</li>
            <li>Advanced Research Track: This track is for students who have demonstrated proficiency in programming and some familiarity with machine learning and statistics. Students here will conduct independent research in tandem with their team and project mentors and will work through advanced computing learning modules. Expectations are for students to complete a research project during the program from design to manuscript.</li>
            <li>Mentor Track: Track for students who have completed 1-2 years of research in the EDIT ML summer program, these students will serve as peer mentors for project teams and contribute to the seminar series and development of educational curriculum. Mentors can also conduct research during this time.</li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <div id="carouselExampleCaptions" class="carousel slide relative" data-bs-ride="carousel">
    <div class="p-6 shadow-lg rounded-lg bg-white text-grey-700">
      <h2 class="font-semibold text-3xl mb-5">Featured Projects</h2>
      <p>
        Our EDIT ML interns have put together some absolutely incredible projects that we are excited to share program faculty and the broader clinical community at Dartmouth Health.
      </p>
      <hr class="my-6 border-gray-300" />
      <p>
        Here are a few featured projects from some of our many all-stars!
      </p>
    </div>
    <div>
      <br>
    </div>
    <div class="carousel-indicators absolute right-0 bottom-0 left-0 flex justify-center p-0 mt-0 mb-2 py-2">
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="1"
        aria-label="Slide 2"></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="2"
        aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner relative w-full overflow-hidden">
      <div class="carousel-item active relative float-left w-full">
        <img
          src="https://user-images.githubusercontent.com/19698023/181658028-55c8907e-f750-4d69-8ba7-14f4ca3f4f35.jpeg"
          class="block w-full"
          alt="..."
        />
        <div class="carousel-caption hidden md:block absolute text-center">
          <h5 class="text-xl text-white">Placeholder- Levy Lab</h5>
          <p>Placeholder- Apply to the <a href="https://levylab.host.dartmouth.edu/">Levy Lab</a> for opportunities in machine learning and health informatics.</p>
        </div>
      </div>
      <div class="carousel-item relative float-left w-full">
        <img
          src="https://user-images.githubusercontent.com/19698023/181657550-f9c375e1-7413-4046-9292-387731a3c8d8.jpeg"
          class="block w-full"
          alt="..."
        />
        <div class="carousel-caption hidden md:block absolute text-center">
          <h5 class="text-xl text-white">Placeholder- Previous Master's student Christian Haudenschild</h5>
          <p>Former QBS Master's student has cat named ChaCha and publishes <a href="/EDIT_AI_virtual_conference/presenter_articles/1_Joshua_Levy.html">multimodal deep learning EHR research</a> under mentorship of Dr. Levy.</p>
        </div>
      </div>
      <div class="carousel-item relative float-left w-full">
        <img
          src="https://user-images.githubusercontent.com/19698023/181657854-47a08806-2d36-40b2-b86d-2d67fd36d1e3.jpeg"
          class="block w-full"
          alt="..."
        />
        <div class="carousel-caption hidden md:block absolute text-center">
          <h5 class="text-xl text-white">Placeholder- Dr. Carly Bobak</h5>
          <p>Placeholder- Learn about Dr. Carly Bobak's innovative work on her <a href="https://www.carlybobak.com/">website</a>.</p>
        </div>
      </div>
    </div>
    <button
      class="carousel-control-prev absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline left-0"
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide="prev">
      <span class="carousel-control-prev-icon inline-block bg-no-repeat" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline right-0"
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide="next">
      <span class="carousel-control-next-icon inline-block bg-no-repeat" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</div>
