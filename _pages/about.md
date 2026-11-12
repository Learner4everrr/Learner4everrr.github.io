---
layout: about
title: about
permalink: /
subtitle: <strong>Ph.D. candidate</strong> in <a href='https://cse.umn.edu/ece'>Electrical and Computer Engineering</a> at the <a href='https://twin-cities.umn.edu/'>University of Minnesota, Twin Cities</a> <br> <em>Creative, Curious, Honest, Passionate</em>

profile:
  align: left
  image: ZZF.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p class="email-contact"><span id="email">zhan8023[at]umn[dot]edu</span>
      <button type="button" class="email-copy" onclick="copyEmail(this)" title="Copy email address" aria-label="Copy email address">
        <i class="fa-regular fa-copy copy-icon" aria-hidden="true"></i>
        <i class="fa-solid fa-check copied-icon" aria-hidden="true" hidden></i>
      </button>
      <span class="email-copy-status" role="status" aria-live="polite"></span>
    </p>
    <script>
      async function copyEmail(button) {
        const status = button.parentElement.querySelector('.email-copy-status');
        button.disabled = true;
        try {
          await navigator.clipboard.writeText('zhan8023@umn.edu');
          button.querySelector('.copy-icon').hidden = true;
          button.querySelector('.copied-icon').hidden = false;
          status.textContent = 'Copied!';
        } catch (err) {
          status.textContent = 'Copy failed. Email: zhan8023@umn.edu';
        }
        setTimeout(() => {
          button.querySelector('.copy-icon').hidden = false;
          button.querySelector('.copied-icon').hidden = true;
          status.textContent = '';
          button.disabled = false;
        }, 2500);
      }
    </script>


news: true # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

<strong>Welcome!</strong>
I am currently pursuing a Ph.D. in Electrical and Computer Engineering at the University of Minnesota, Twin Cities, with an anticipated completion in 2026. Prior to this, I earned a Master of Engineering in Electrical Engineering from <a href='https://www.tsinghua.edu.cn/en/'>Tsinghua University</a> in 2021 and a Bachelor of Science in Electrical Engineering from <a href='http://en.njtu.edu.cn/'>Beijing Jiaotong University</a> in 2018.
Currently, I am fortunately advised by <a href='https://med.umn.edu/bio/rui-zhang'>Prof.Zhang</a> at the <a href='https://ruizhang.umn.edu/'>Zhang Research Group</a>.

<strong>Research Interests</strong>: I am passionate about machine learning, natural language processing and computer vision. I enjoy appling state-of-the-art techniques to tackle real-world problems. Through my work, I aim to develop innovative tools and solutions that empower industries and advance scientific knowledge.
Let’s connect and explore how we can collaborate! 😊 

<strong>Skills</strong>:<br> 
Programming: <em>Python(Proficient), MATLAB(Proficient), SQL, R, C/C++, Java </em><br> 
Frameworks: <em>PyTorch, TensorFlow, Scikit-learn, Hugging Face, vLLM </em><br> 
Math: <em>Linear Algebra, Probability & Statistics, Convex and integer optimization, Common ML Algorithms, DL basics </em> <br> 
Data Processing: <em>Pandas, NumPy, Data Cleaning, Data Visualization (Matplotlib, Seaborn) </em><br> 
Others: <em>Linux Bash, Shell, Git, GitHub, Slurm, LaTeX, Processing, Jupyter </em><br>


<strong>Reviewer Service</strong>:<br> 
<strong>Journal</strong>: <em>Nature Communications(if=18.1 2026), npj Digital Medicine(if=18.1 2026), JAMIA open, npj Precision Oncology, IEEE Journal of Biomedical and Health Informatics, JMIR Medical Informatics, International Journal of Computers and Applications, Applied Artificial Intelligence, Scientific Report, Discover Computing, Discover Education, PeerJ Computer Science, Digital Health, Journal of King Saud University Computer and Information Sciences, BMC Medical Informatics, BMC Medical Informatics and Decision Making, BMC Medical Education, BMC Medical Research Methodology, BMC Medical Imaging, Communications Medicine, Information Processing and Management, Expert Systems With Applications, International Journal of Data Science and Analytics, Informatics in Medicine Unlocked, Network Modeling Analysis in Health Informatics and Bioinformatics, European Journal of Cancer, Psychology, Health & Medicine, Discover Artificial Intelligence, Discover Informatics, Cluster Computing, Journal of Experimental & Theoretical Artificial Intelligence, BMC Cardiovascular Disorders, International Journal of Machine Learning and Cybernetics, Applied Soft Computing Journal, International Journal of Digital Earth, Journal of Imaging Informatics in Medicine, Knowledge-Based Systems, Intelligence-Based Medicine, Computer Methods and Programs in Biomedicine Update </em> <br> 
<strong>Conference</strong>: <em>AMIA Annual Symposium'25, ACL-SRW'25, ICNLSP'25 (Program Committee), ACL'25, Amplify Informatics Conference'26, IEEE ICHI'26, AMIA Annual Symposium'26, ICNLSP'26, AAAI'27 </em> <br> 
