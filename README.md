<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Preview GitHub Profile</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/5.2.0/github-markdown.min.css">
<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
<style>
    body {
        box-sizing: border-box;
        min-width: 200px;
        max-width: 980px;
        margin: 0 auto;
        padding: 45px;
        background-color: #0d1117; /* Dark mode background approximation */
    }
    @media (max-width: 767px) {
        body {
            padding: 15px;
        }
    }
    .markdown-body {
        background-color: #0d1117;
        color: #c9d1d9;
    }
    /* Fix for images in readme to prevent overflow */
    img {
        max-width: 100%;
    }
    /* Center aligns usually look good for badges but default is left */
    h1, h2, h3 {
        border-bottom-color: #21262d;
        color: #e6edf3;
    }
    a {
        color: #58a6ff;
    }
    /* Utility for side-by-side images in preview */
    .row {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .col {
        width: 48%;
    }
</style>
</head>
<body>
    <article class="markdown-body" id="content">
    </article>
    <script>
        // Nội dung Markdown từ user
        // Lưu ý: Trong thực tế GitHub README, chúng ta dùng <img align="left"> và <img align="right">.
        // Ở đây tôi mô phỏng lại cấu trúc đó để hiển thị đúng trên Preview.
        const markdownContent = `
### Hi 👋

### :man_technologist: About Me :
- :telescope: I am currently working on Unity Project 2d and 3D
In the near future, i will switch into Shopify, Work with Database, etc..

- :seedling: Exploring Technical Content Writing.

- :zap: In my free time, I solve problems on GeeksforGeeks and read tech articles.

- :mailbox:How to reach me: [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/dinhdungvan)
---


## 🌐Socials
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/dinhdungvan) [![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/19370831) [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/@shaiko4215) 

# 💻Tech Stack
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white) ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![Angular.js](https://img.shields.io/badge/angular.js-%23E23237.svg?style=for-the-badge&logo=angularjs&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Adobe After Effects](https://img.shields.io/badge/Adobe%20After%20Effects-9999FF.svg?style=for-the-badge&logo=Adobe%20After%20Effects&logoColor=white) ![Adobe Audition](https://img.shields.io/badge/Adobe%20Audition-9999FF.svg?style=for-the-badge&logo=Adobe%20Audition&logoColor=white) ![Adobe Illustrator](https://img.shields.io/badge/adobeillustrator-%23FF9A00.svg?style=for-the-badge&logo=adobeillustrator&logoColor=white) ![Adobe Photoshop](https://img.shields.io/badge/adobephotoshop-%2331A8FF.svg?style=for-the-badge&logo=adobephotoshop&logoColor=white) ![Adobe Premiere Pro](https://img.shields.io/badge/Adobe%20Premiere%20Pro-9999FF.svg?style=for-the-badge&logo=Adobe%20Premiere%20Pro&logoColor=white) 	![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white)

# 📊GitHub Stats :
<div style="display: flex; justify-content: space-between; align-items: center;">
  <img src="https://github-readme-stats.vercel.app/api?username=shaikowannasleep&theme=onedark&hide_border=false&include_all_commits=true&count_private=false" style="width: 48%; height: auto;" />
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODY5aHFxcGJqc284eHEwZGhvYWZvaXM1bWx0dGV6djJubGp3anRsYyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/yedDQGWwq0heU/giphy.gif" style="width: 48%; height: auto;" />
</div>
<br/>
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shaikowannasleep&theme=onedark&hide_border=false&include_all_commits=true&count_private=false&layout=compact" width="100%"/>
</div>
        `;
        document.getElementById('content').innerHTML = marked.parse(markdownContent);
    </script>
</body>
</html>
