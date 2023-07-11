<div align="center">
<a href="https://ibb.co/KWkc3Gw"><img src="https://i.ibb.co/6FxcfZB/ddf604h-fec4abb5-e6b5-4f26-8868-587d1fb0525f.png" alt="anime-dr-stone-senku-ishigami-hd-wallpaper-preview" border="0"></a>

#**SENKU : ANIME THEMED WHATSAPP BOT WITH RICH FEATURES BASED ON RIN**

[![CodeFactor](https://www.codefactor.io/repository/github/oreki-san/rin/badge)](https://www.codefactor.io/repository/github/oreki-san/rin)

## [![WhatsApp Group](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)]() [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![NodeJs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/en/)

> A Fully Modular and Efficient Bot <br>

Button : If you are deploying normally


[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/AdithyanKenzo/SENKU.git)

Button : If you are deploying from a fork

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

</div><br/>
<br/>

## ✨ Highlights

-   Fully Modular Design
-   Object Oriented
-   Written in [TypeScript](https://www.typescriptlang.org/)
-   Self-Restoring Auth
-   Built with [Baileys](https://github.com/adiwajshing/baileys) (The Best
    WhatsApp Library Out There)

## 💻 Deploy/Hosting Guide

-   Section Moved to
    [SENKU-Guides](https://github.com/AdithyanKenzo/SENKU/blob/main/README.md)

## 🍥 Features of the Repo

-   To view all features, click
    here➡️[Kaoi_featuresList.md](https://github.com/PrajjwalDatir/Kaoi/blob/main/Features.md)

## 💪 Contribution

-   Feel free to open issues regarding any problems or if you have any feature
    requests
-   Make sure to follow the ESLint Rules while editing the code and run
    `yarn run prettier-format` before opening PRs
## Give a ⭐ if this project helped you

## 🚀Some WhatsApp bots are recommended🚀
<details>
<summary>Click Here</summary>

![Kaoi][![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=PrajjwalDatir&repo=Kaoi&theme=buefy)](https://github.com/PrajjwalDatir/kaoi)

![Chitoge][![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=ShineiIchijo&repo=Chitoge&theme=buefy)](https://github.com/ShinNouzen/Chitoge)

  <h1>GitHub Commits</h1>
  <div id="commits"></div>

  <script>
    // GitHub repository information
    const username = 'AdithyanKenzo';
    const repository = 'SENKU';
    const contributors = ['NemasisDarkX'];

    // Fetch commits for each contributor
    const fetchCommits = async () => {
      const commitsElement = document.getElementById('commits');

      for (const contributor of contributors) {
        const apiUrl = `https://api.github.com/repos/${username}/${repository}/commits?author=${contributor}`;

        try {
          const response = await fetch(apiUrl);
          const data = await response.json();
          const commitCount = data.length;

          // Display the number of commits for the contributor
          commitsElement.innerHTML += `<p>Commits by ${contributor}: ${commitCount}</p>`;
        } catch (error) {
          console.error(`Error fetching commits for ${contributor}:`, error);
          commitsElement.innerHTML += `<p>Error fetching commits for ${contributor}</p>`;
        }
      }
    };

    // Call the fetchCommits function
    fetchCommits();
  </script>

