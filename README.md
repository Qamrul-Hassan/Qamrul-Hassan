// pages/profile.js
import React from "react";

const Profile = () => {
  return (
    <div>
      <header>
        <h1>Hi there 👋, I'm Qamrul Hassan Shajal</h1>
        <img
          src="https://pbs.twimg.com/profile_banners/247298919/1725556021/1500x500"
          alt="Web Developer"
        />
      </header>

      <section>
        <p>
          I'm a passionate beginner web developer diving deep into HTML, CSS, Bootstrap, Tailwind, JavaScript, and React.
          My journey into web development is driven by a love for creating intuitive, user-friendly websites. I’m excited to share my projects and growth as I explore new tools and technologies...
        </p>
      </section>

      <section>
        <h3>🛠️ Skills</h3>
        <div>
          <img
            src="https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"
            alt="HTML5"
          />
          <img
            src="https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=css3&logoColor=white"
            alt="CSS3"
          />
          <img
            src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black"
            alt="JavaScript"
          />
          <img
            src="https://img.shields.io/badge/Bootstrap-563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white"
            alt="Bootstrap"
          />
          <img
            src="https://img.shields.io/badge/TailwindCSS-38B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white"
            alt="TailwindCSS"
          />
          <img
            src="https://img.shields.io/badge/React-61DAFB.svg?style=for-the-badge&logo=react&logoColor=black"
            alt="React"
          />
        </div>
      </section>

      <section>
        <h3>🔭 Current Projects</h3>
        <ul>
          <li>Building responsive websites with HTML, CSS, and Bootstrap.</li>
          <li>Experimenting with Tailwind for utility-first CSS design.</li>
          <li>Using JavaScript and React to add dynamic, interactive elements.</li>
        </ul>
      </section>

      <section>
        <h3>🎯 Goals for 2024</h3>
        <ul>
          <li>Build a fully responsive website from scratch.</li>
          <li>Contribute to open-source projects.</li>
          <li>Master JavaScript and dive deeper into React.</li>
        </ul>
      </section>

      <section>
        <h3>📫 Let's Connect</h3>
        <div>
          <a href="https://www.linkedin.com/in/qamrul-hassan-a9b0a231/" target="_blank" rel="noopener noreferrer">
            <img
              src="https://img.shields.io/badge/LinkedIn-0077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"
              alt="LinkedIn"
            />
          </a>
          <a href="https://x.com/Shajal1" target="_blank" rel="noopener noreferrer">
            <img
              src="https://img.shields.io/badge/Twitter-1DA1F2.svg?style=for-the-badge&logo=twitter&logoColor=white"
              alt="Twitter"
            />
          </a>
          <a href="https://www.facebook.com/qamrul.h.shajal" target="_blank" rel="noopener noreferrer">
            <img
              src="https://img.shields.io/badge/Facebook-1877F2.svg?style=for-the-badge&logo=facebook&logoColor=white"
              alt="Facebook"
            />
          </a>
        </div>
      </section>

      <section>
        <h3>🏆 GitHub Trophies</h3>
        <a href="https://github.com/ryo-ma/github-profile-trophy">
          <img
            src="https://github-profile-trophy.vercel.app/?username=Qamrul-Hassan&theme=onedark&row=1&column=7"
            alt="GitHub Trophies"
          />
        </a>
      </section>

      <section>
        <h3>📊 GitHub Stats</h3>
        <img
          src="https://github-readme-stats.vercel.app/api?username=Qamrul-Hassan&show_icons=true&theme=onedark&count_private=true"
          alt="GitHub Stats"
        />
        <img
          src="https://github-readme-streak-stats.herokuapp.com/?user=Qamrul-Hassan&theme=onedark"
          alt="GitHub Streaks"
        />
        <img
          src="https://github-readme-stats.vercel.app/api/top-langs/?username=Qamrul-Hassan&layout=compact&theme=onedark&langs_count=8"
          alt="Top Languages"
        />
      </section>

      <section>
        <h3>🛠️ Development Tools</h3>
        <a href="https://archiveprogram.github.com/">
          <img
            src="https://raw.githubusercontent.com/acervenky/animated-github-badges/master/assets/acbadge.gif"
            alt="GitHub Archive"
            width="50"
            height="50"
          />
        </a>
      </section>

      <footer>
        <p>© 2024 Qamrul Hassan - All Rights Reserved</p>
      </footer>
    </div>
  );
};

export default Profile;
