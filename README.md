#### 👋 HELLO

Thank you for visiting my GitHub page.

I am currently immersed in the study of data engineering and bring with me two years of experience as a numerical analysis developer. Beyond my focus on data engineering and quant development, I maintain a wide-ranging interest in various programming languages and theories. My goal is to discover improved solutions by exploring and mastering new technologies and tools.

I will be documenting my studies and challenges right here on my GitHub. Despite the prevalence of English among users, I've decided to primarily compose my posts in my native language, Korean. This choice is driven by my commitment to keeping my records concise and dedicating more time to the study of computer programming. If you ever find the need for English translations to understand my content, please do not hesitate to ask me for assistance.

As a developer who values opportunities for communication and sharing, I am excited about the prospect of growing and learning together. Please feel free to reach out at any time.

Best regards,  
SeminarNotes
<div class="container">
  <div class="overlay"></div>
  <div class="card"></div>
</div>

<script>
  var container = document.querySelector('.container')
  var overlay = document.querySelector('.overlay')
  container.addEventListener('mousemove', function(e){
    var x = e.offsetX
    var y = e.offsetY
    var rotateY = -1/5 * x + 20
    var rotateX = 4/30 * y - 20

    overlay.style = `background-position : ${x/5 + y/5}%; filter : opacity(${x/200}) brightness(1.2)`

    container.style = `transform : perspective(350px) rotateX(${rotateX}deg) rotateY(${rotateY}deg)`
  })

  container.addEventListener('mouseout', function(){
    overlay.style = 'filter : opacity(0)'
    container.style = 'transform : perspective(350px) rotateY(0deg) rotateX(0deg)'
  })


</script>

<style>
  .container {
    width: 220px; height: 310px; transition : all 0.1s;
    position: relative;
  }
  .overlay {
    position: absolute;
    width: 220px;
    height: 310px;
    background: linear-gradient(105deg,
    transparent 40%,
    rgba(255, 219, 112, 0.8) 45%,
    rgba(132, 50, 255 ,0.6) 50%,
    transparent 54%);
    filter: brightness(1.1) opacity(0.8);
    mix-blend-mode: color-dodge;
    background-size: 150% 150%;
    background-position: 100%;
    transition: all 0.1s;
  }
  .card {
    width: 220px; height: 310px;
    background-image: url(pika.webp);
    background-size: cover;
  }
</style>


#### 📚 STREAK

[![GitHub Streak](https://streak-stats.demolab.com?user=seminarNotes&locale=ko&card_width=500)](https://git.io/streak-stats)


#### 📚 STACKS
Programming Languages:
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=C&logoColor=white">

Python Libraries:
<img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=for-the-badge&logo=Tensorflow&logoColor=white"> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white"> <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=Selenium&logoColor=white"> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white"> 

Frameworks:
<img src="https://img.shields.io/badge/Apache Airflow-017CEE?style=for-the-badge&logo=Apache Airflow&logoColor=white">

Databases:
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/mariaDB-003545?style=for-the-badge&logo=mariaDB&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">

Container Engine:
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"> 

Search Engine:
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=Elasticsearch&logoColor=white">

Operating System: <img src="https://img.shields.io/badge/windows-0078D4?style=for-the-badge&logo=windows&logoColor=black">
<img src="https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=seminarNotes&layout=compact"><br><br>











<!--
**seminarNotes/seminarNotes** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=seminarNotes&layout=compact"><br><br>
<img src="https://github-readme-stats.vercel.app/api?username=seminarNotes&show_icons=true">

-->
