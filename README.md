

<!--
**yoojinlee-hub/yoojinlee-hub** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
### 
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
|Yoojinlee's github 👋 | https://blog.naver.com/agleejean |


<!DOCTYPE html>
<html lang="ko-kr">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>D-Day</title>
  </head>
  <body
    style="
      display: flex;
      flex: 1;
      align-items: center;
      justify-content: center;
      padding: 0 4px;
    "
  ></body>
  <script src="https://unpkg.com/dayjs@1.8.21/dayjs.min.js"></script>
  <script>
    const formatMap = {
      minute: "분",
      hour: "시간",
      day: "일",
      month: "개월",
      year: "년"
    };

    function spaceReplacer(str) {
      return str.replace(/-/g, " ");
    }

    window.onload = function () {
      const params = new URLSearchParams(window.location.search);
      const align = params.get("align") || "left";
      const color = params.get("color") || "black";
      const bgColor = params.get("bg-color") || "white";

      const format = params.get("format") || "month";
      const sinceDateString = params.get("since") || "2023-01-01";

      const prefix = params.get("prefix") ? params.get("prefix") + " " : "";
      const suffix = params.get("suffix") ? " " + params.get("suffix") : "";

      const since = dayjs(sinceDateString);
      const now = dayjs();
      const diff = now.diff(since, format);

      const h2 = document.createElement("h2");
      h2.setAttribute("style", `flex:1; text-align:${align}; color:${color}`);
      h2.innerText = `${spaceReplacer(prefix)}${diff}${
        formatMap[format]
      }${spaceReplacer(suffix)}`;
      document.body.append(h2);
      document.body.parentElement.setAttribute(
        "style",
        `display: flex; flex: 1; height: 100%; background-color:${bgColor};`
      );
    };
  </script>
</html>

|--|--------|
|⚡My stats|[![Yoojin's GitHub stats](https://github-readme-stats.vercel.app/api?username=yoojinlee-hub)](https://github.com/yoojinlee-hub/github-readme-stats)|
|🏆award-winning work(worked with others)🏆|<a href="https://github.com/yoojinlee-hub/NPC_Project"><img src="https://img.shields.io/badge/NPC_project(Game/RPGmaker)-7878FF?style=flat-square&logo=GitHub&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/DALC_3_3"><img src="https://img.shields.io/badge/DALC_project(Web with AI)-28288C?style=flat-square&logo=GitHub&logoColor=white"/></a>|
|✍Studying✍|<a href="https://github.com/yoojinlee-hub/Recommended-skills_Study_by_python"><img src="https://img.shields.io/badge/AI Study-FF9CBB?style=flat-square&logo=Jupyter&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/Practice_python"><img src="https://img.shields.io/badge/Python-FF5675?style=flat-square&logo=Python&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/DALC_Scala"><img src="https://img.shields.io/badge/AI Study in DALC-F37626?style=flat-square&logo=Jupyter&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/website_practice"><img src="https://img.shields.io/badge/Website-FF9614?style=flat-square&logo=HTML5&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/Practice_Javascript"><img src="https://img.shields.io/badge/JavaScript-FFD200?style=flat-square&logo=JavaScript&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/Practice_WebReact"><img src="https://img.shields.io/badge/WebReact-61DAFB?style=flat-square&logo=React&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/React-youtube-clone"><img src="https://img.shields.io/badge/React_youtube_clone-61DAFB?style=flat-square&logo=React&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/Practice_C"><img src="https://img.shields.io/badge/C-BC55EF?style=flat-square&logo=C&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/Practice_JAVA"> <a href="https://github.com/yoojinlee-hub/Practice_Kotlin"><img src="https://img.shields.io/badge/Kotlin-9282CD?style=flat-square&logo=Kotlin&logoColor=white"/></a> <img src="https://img.shields.io/badge/Java-DD78F6?style=flat-square&logo=Java&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/Practice_LUA"><img src="https://img.shields.io/badge/Lua-E47AE0?style=flat-square&logo=Lua&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/Practice_SQL"><img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=SQL&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/Math_box"><img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/></a>|
|🚩Studying certification🚩|<a href="https://github.com/yoojinlee-hub/Linux_Master"><img src="https://img.shields.io/badge/Linux Master-FCC624?style=flat-square&logo=Linux&logoColor=white"/></a> <a href="https://github.com/yoojinlee-hub/networkManager_certification"><img src="https://img.shields.io/badge/networkManager-2E75B4?style=flat-square&logo=Li&logoColor=white"/></a>|
* What is DALC ? Dongduk AI Learning Crew ( AI club in Univ)
