<style>
@keyframes neon-glow {
  0%, 100% {
    box-shadow: 0 0 10px #2E9EF7, 0 0 20px #2E9EF7, inset 0 0 10px rgba(46, 158, 247, 0.5);
  }
  50% {
    box-shadow: 0 0 20px #2E9EF7, 0 0 40px #2E9EF7, 0 0 60px #2E9EF7, inset 0 0 20px rgba(46, 158, 247, 0.8);
  }
}

@keyframes border-travel {
  0% {
    background: linear-gradient(90deg, transparent, transparent, #2E9EF7, transparent, transparent);
    background-position: 0% center;
  }
  50% {
    background: linear-gradient(90deg, transparent, #2E9EF7, #00FFFF, #2E9EF7, transparent);
    background-position: 100% center;
  }
  100% {
    background: linear-gradient(90deg, transparent, transparent, #2E9EF7, transparent, transparent);
    background-position: 200% center;
  }
}

@keyframes border-travel-vertical {
  0% {
    background: linear-gradient(180deg, transparent, transparent, #2E9EF7, transparent, transparent);
    background-position: center 0%;
  }
  50% {
    background: linear-gradient(180deg, transparent, #2E9EF7, #00FFFF, #2E9EF7, transparent);
    background-position: center 100%;
  }
  100% {
    background: linear-gradient(180deg, transparent, transparent, #2E9EF7, transparent, transparent);
    background-position: center 200%;
  }
}

.neon-border {
  position: relative;
  border: 2px solid transparent;
  background-clip: padding-box;
  animation: neon-glow 2s ease-in-out infinite;
}

.neon-border::before {
  content: '';
  position: absolute;
  top: -2px;
  left: -2px;
  right: -2px;
  height: 2px;
  background: linear-gradient(90deg, transparent, #2E9EF7, #00FFFF, #2E9EF7, transparent);
  background-size: 200% 100%;
  animation: border-travel 3s ease-in-out infinite;
}

.neon-border::after {
  content: '';
  position: absolute;
  bottom: -2px;
  left: -2px;
  right: -2px;
  height: 2px;
  background: linear-gradient(270deg, transparent, #2E9EF7, #00FFFF, #2E9EF7, transparent);
  background-size: 200% 100%;
  animation: border-travel 3s ease-in-out infinite reverse;
}

.neon-side-left {
  position: absolute;
  top: -2px;
  left: -2px;
  width: 2px;
  bottom: -2px;
  background: linear-gradient(180deg, transparent, #2E9EF7, #00FFFF, #2E9EF7, transparent);
  background-size: 100% 200%;
  animation: border-travel-vertical 3s ease-in-out infinite;
}

.neon-side-right {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 2px;
  bottom: -2px;
  background: linear-gradient(360deg, transparent, #2E9EF7, #00FFFF, #2E9EF7, transparent);
  background-size: 100% 200%;
  animation: border-travel-vertical 3s ease-in-out infinite reverse;
}
</style>

<div align="center">

<div class="neon-border" style="padding: 20px; border-radius: 10px;">
  <div class="neon-side-left"></div>
  <div class="neon-side-right"></div>
  
  <a href="#">
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&duration=3000&pause=1200&color=2E9EF7&center=true&vCenter=true&multiline=true&width=750&height=110&lines=Backend+Engineer+%7C+Full+Stack+Developer&lines=Java+%7C+Spring+Boot+%7C+Python+%7C+React+%7C+Angular+%7C+Cloud" alt="Backend Engineer" />
  </a>
</div>

<br/>

[![Resume](https://img.shields.io/badge/Resume-View-2E9EF7?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/14fGbFIg_VL3VPDn-BzjRJ7vH7MHy4bTS/view?usp=sharing)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rupesh-borse)
[![Gmail](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rupeshborse45@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/rupeshborse_)

![Profile Views](https://komarev.com/ghpvc/?username=rupeshrb&color=2E9EF7&style=flat-square&label=PROFILE+VIEWS)
![Location](https://img.shields.io/badge/📍-Pune,%20India-informational?style=flat-square)
![Status](https://img.shields.io/badge/💼-Eaton%20Corporation-informational?style=flat-square)

</div>

<br/>

<div align="center" class="neon-border" style="padding: 20px; border-radius: 10px; margin: 20px auto; max-width: 800px;">
  <div class="neon-side-left"></div>
  <div class="neon-side-right"></div>
  
  I build secure, scalable backend systems — REST & gRPC services, event-driven pipelines with **Kafka** and **Redis**, and full-stack apps with **Angular** and **React**. At **Eaton Corporation**, I architect robust solutions that power critical infrastructure globally.

</div>

<br/>

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,python,js,ts,cpp,react,angular,django,flask,fastapi,mysql,postgres,mongodb,redis,docker,azure,nginx,git,githubactions,html,css&theme=dark&perline=12" alt="Tech Stack" />

</div>

<br/>

<div align="center" class="neon-border" style="padding: 20px; border-radius: 10px;">
  <div class="neon-side-left"></div>
  <div class="neon-side-right"></div>

  <img src="https://streak-stats.demolab.com?user=rupeshrb&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rupeshrb/rupeshrb/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rupeshrb/rupeshrb/output/github-contribution-grid-snake.svg" />
    <img alt="contribution snake animation" src="https://raw.githubusercontent.com/rupeshrb/rupeshrb/output/github-contribution-grid-snake.svg" width="100%"/>
  </picture>

</div>
