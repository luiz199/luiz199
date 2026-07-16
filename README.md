<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0A0A,50:FF6B00,100:0A0A0A&height=200&section=header&text=LUIZ%20HENRIQUE&fontSize=60&fontColor=FFFFFF&animation=fadeIn&fontAlignY=36&desc=Data%20%26%20AI%20Engineer%20%7C%20Computer%20Science%20Graduate&descAlignY=55&descAlign=50" width="100%" />
</p>

```text
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║   █████╗ ██████╗  ██████╗ ██╗   ██╗████████╗    ███╗   ███╗██╗███╗   ██╗██████╗  ║
║  ██╔══██╗██╔══██╗██╔═══██╗╚██╗ ██╔╝╚══██╔══╝    ████╗ ████║██║████╗  ██║██╔══██╗ ║
║  ███████║██████╔╝██║   ██║ ╚████╔╝    ██║       ██╔████╔██║██║██╔██╗ ██║██║  ██║ ║
║  ██╔══██║██╔══██╗██║   ██║  ╚██╔╝     ██║       ██║╚██╔╝██║██║██║╚██╗██║██║  ██║ ║
║  ██║  ██║██║  ██║╚██████╔╝   ██║      ██║       ██║ ╚═╝ ██║██║██║ ╚████║██████╔╝ ║
║  ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝    ╚═╝      ╚═╝       ╚═╝     ╚═╝╚═╝╚═╝  ╚═══╝╚═════╝  ║
║                                                                              ║
║                  Mathematics · Computer Science · Artificial Intelligence    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&duration=2500&pause=500&color=FF6B00&center=true&vCenter=true&random=false&width=700&height=50&lines=%22First%2C+solve+the+problem.+Then%2C+write+the+code.%22;%22Simplicity+is+prerequisite+for+reliability.%22;%22Talk+is+cheap.+Show+me+the+code.%22;%22Make+it+work%2C+make+it+right%2C+make+it+fast.%22" alt="Typing Quotes" />
</p>

<br />

---

<p align="center">
  <a href="https://www.linkedin.com/in/luiz-henrique-souza-da-silva-17252b403"><img src="https://img.shields.io/badge/LinkedIn-FF6B00?style=for-the-badge&logo=linkedin&logoColor=0A0A0A&labelColor=0A0A0A" /></a>
  <a href="https://lattes.cnpq.br/7486657973350349"><img src="https://img.shields.io/badge/Lattes-FF6B00?style=for-the-badge&logo=googlescholar&logoColor=FF6B00&labelColor=0A0A0A" /></a>
  <a href="https://www.instagram.com/aidatamind"><img src="https://img.shields.io/badge/Instagram-FF6B00?style=for-the-badge&logo=instagram&logoColor=FF6B00&labelColor=0A0A0A" /></a>
  <a href="https://github.com/luiz199"><img src="https://img.shields.io/badge/GitHub-FF6B00?style=for-the-badge&logo=github&logoColor=FF6B00&labelColor=0A0A0A" /></a>
</p>

---

## system/profiler

```c
#include <stdio.h>
#include <string.h>
#include <stdbool.h>

typedef enum {
    MATHEMATICS = 0x01,
    COMPUTER_SCIENCE,
    DATA_ENGINEERING,
    AI_ENGINEERING,
    FULL_STACK
} Domain;

typedef struct {
    char        name[24];
    char        location[32];
    Domain      domain;
    int         experience_years;
    char        education[3][48];
    char        skills[12][24];
    bool        available;
    const char *motto;
} Engineer;

int main() {
    Engineer me = {
        .name            = "Luiz Henrique",
        .location        = "Rio Branco, AC, Brazil",
        .domain          = COMPUTER_SCIENCE,
        .experience_years = 4,
        .education       = {
            "B.Sc. Mathematics & Computer Science — UNIBF",
            "MBA Data Warehouse & Business Intelligence — UNIBF",
            "B.Ed. Mathematics — UNOPAR"
        },
        .skills          = {
            "TypeScript", "Python", "React/Next.js",
            "Node.js",    "Tailwind CSS", "Framer Motion",
            "MongoDB",    "OpenAI",       "NestJS",
            "Git",        "REST APIs",    "Cloud/Vercel"
        },
        .available       = true,
        .motto           = "Transform complex problems into elegant digital solutions."
    };

    printf("┌─────────────────────────────────┐\n");
    printf("│  %-31s │\n", me.name);
    printf("│  %-31s │\n", me.location);
    printf("├─────────────────────────────────┤\n");
    printf("│  Domain:  Computer Science      │\n");
    printf("│  Status:  %s                  │\n", me.available ? "Available" : "Busy");
    printf("└─────────────────────────────────┘\n");

    return 0;
}
```

<br />

---

## repository/featured

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🌤 Datamind Weather</h3>
      <sub><code>Next.js · TypeScript · Tailwind · Framer Motion · OpenWeather</code></sub>
      <br /><br />
      <a href="https://github.com/luiz199/datamind-weather">
        <img src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=luiz199&repo=datamind-weather&bg_color=0A0A0A&title_color=FF6B00&text_color=ffffff&icon_color=FF6B00&border_color=FF6B0040&hide_border=true" width="100%" />
      </a>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 Aura AI</h3>
      <sub><code>TypeScript · OpenAI · NLP · Process Automation</code></sub>
      <br /><br />
      <a href="https://github.com/luiz199/aura-ai">
        <img src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=luiz199&repo=aura-ai&bg_color=0A0A0A&title_color=FF6B00&text_color=ffffff&icon_color=FF6B00&border_color=FF6B0040&hide_border=true" width="100%" />
      </a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🍽 RESTAU MASTER PRO</h3>
      <sub><code>HTML5 · JavaScript · LocalStorage · PWA</code></sub>
      <br /><br />
      <a href="https://github.com/luiz199/professional-systems">
        <img src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=luiz199&repo=professional-systems&bg_color=0A0A0A&title_color=FF6B00&text_color=ffffff&icon_color=FF6B00&border_color=FF6B0040&hide_border=true" width="100%" />
      </a>
    </td>
    <td width="50%" valign="top">
      <h3>💪 FitManager Pro</h3>
      <sub><code>Alpine.js · Tailwind CSS · IndexedDB</code></sub>
      <br /><br />
      <a href="https://github.com/luiz199/professional-systems">
        <img src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=luiz199&repo=professional-systems&bg_color=0A0A0A&title_color=FF6B00&text_color=ffffff&icon_color=FF6B00&border_color=FF6B0040&hide_border=true" width="100%" />
      </a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🐾 NeoVet</h3>
      <sub><code>Next.js · Tailwind · Framer Motion · Recharts</code></sub>
      <br /><br />
      <a href="https://github.com/luiz199/professional-systems/tree/master/neovet">
        <img src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=luiz199&repo=professional-systems&bg_color=0A0A0A&title_color=FF6B00&text_color=ffffff&icon_color=FF6B00&border_color=FF6B0040&hide_border=true" width="100%" />
      </a>
    </td>
    <td width="50%" valign="top">
      <h3>💼 Portfolio CS</h3>
      <sub><code>Alpine.js · Tailwind · Canvas API · i18n · PWA</code></sub>
      <br /><br />
      <a href="https://luiz199.github.io/professional-systems/portfolio/">
        <img src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=luiz199&repo=professional-systems&bg_color=0A0A0A&title_color=FF6B00&text_color=ffffff&icon_color=FF6B00&border_color=FF6B0040&hide_border=true" width="100%" />
      </a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎁 Mimos Personalizados</h3>
      <sub><code>Next.js · TypeScript · Tailwind · Framer Motion</code></sub>
      <br /><br />
      <a href="https://github.com/luiz199/mimos-personalizados">
        <img src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=luiz199&repo=mimos-personalizados&bg_color=0A0A0A&title_color=FF6B00&text_color=ffffff&icon_color=FF6B00&border_color=FF6B0040&hide_border=true" width="100%" />
      </a>
    </td>
    <td width="50%" valign="top">
      <h3>📚 EduPlan Manager</h3>
      <sub><code>TypeScript · CRUD · Scheduling · Reporting</code></sub>
      <br /><br />
      <a href="https://github.com/luiz199/datamind-school-system">
        <img src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=luiz199&repo=datamind-school-system&bg_color=0A0A0A&title_color=FF6B00&text_color=ffffff&icon_color=FF6B00&border_color=FF6B0040&hide_border=true" width="100%" />
      </a>
    </td>
  </tr>
</table>

<br />

---

## stack/technology

```text
FRONTEND        │  Next.js  React  TypeScript  Tailwind CSS  Alpine.js  Framer Motion
BACKEND         │  Node.js  Python  NestJS  OpenAI  Ollama  REST APIs
DATABASE        │  MongoDB  PostgreSQL  LocalStorage  IndexedDB
DEVOPS & TOOLS  │  Git  Vercel  Puppeteer  OpenWeather  Recharts
LANGUAGES       │  TypeScript  JavaScript  Python  HTML/CSS  C
```

<br />

---

## github/metrics

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=luiz199&show_icons=true&count_private=true&title_color=FF6B00&icon_color=FF6B00&text_color=ffffff&bg_color=0A0A0A&border_color=FF6B0040&hide_border=false&include_all_commits=true" />
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=luiz199&layout=compact&title_color=FF6B00&text_color=ffffff&bg_color=0A0A0A&border_color=FF6B0040&hide_border=false&langs_count=8" />
</p>

<p align="center">
  <img width="49%" src="https://streak-stats.demolab.com?user=luiz199&theme=dark&background=0A0A0A&border=FF6B0040&ring=FF6B00&fire=FF6B00&currStreakNum=FF6B00&sideNums=FF6B00&currStreakLabel=FF6B00&sideLabels=FF6B00&dates=888888" />
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=luiz199&theme=dark&utcOffset=-3" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=luiz199&custom_title=Contribution%20Activity&bg_color=0A0A0A&color=FF6B00&line=FF6B00&point=FFFFFF&area=true&area_color=FF6B0020&hide_border=true&radius=8" width="98%" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=luiz199&theme=darkhub&no-frame=true&no-bg=true&column=4&margin-w=15&margin-h=15&rank=S,AAA,AA,A,B,C" width="98%" />
</p>

<br />

---

## contact/channels

<p align="center">
  <a href="https://www.linkedin.com/in/luiz-henrique-souza-da-silva-17252b403">
    <img src="https://img.shields.io/badge/LinkedIn-0A0A0A?style=for-the-badge&logo=linkedin&logoColor=FF6B00&label=luiz-henrique-souza-da-silva" />
  </a>
  <a href="https://www.instagram.com/aidatamind">
    <img src="https://img.shields.io/badge/Instagram-0A0A0A?style=for-the-badge&logo=instagram&logoColor=FF6B00&label=@aidatamind" />
  </a>
  <a href="https://lattes.cnpq.br/7486657973350349">
    <img src="https://img.shields.io/badge/Lattes-0A0A0A?style=for-the-badge&logo=googlescholar&logoColor=FF6B00" />
  </a>
  <a href="https://github.com/luiz199">
    <img src="https://img.shields.io/badge/GitHub-0A0A0A?style=for-the-badge&logo=github&logoColor=FF6B00&label=luiz199" />
  </a>
</p>

<p align="center">
  <sub>
    <code>📍 Rio Branco, Acre, Brazil</code>&nbsp;&nbsp;
    <code>🎓 B.Sc. Mathematics & Computer Science</code>&nbsp;&nbsp;
    <code>📧 luiz199.github.io</code>
  </sub>
</p>

<br />

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=luiz199&color=FF6B00&style=flat-square&label=PROFILE+VIEWS" />
  &nbsp;&nbsp;
  <img src="https://img.shields.io/github/followers/luiz199?style=flat-square&color=FF6B00&label=FOLLOWERS" />
  &nbsp;&nbsp;
  <img src="https://img.shields.io/github/stars/luiz199?style=flat-square&color=FF6B00&label=STARS" />
</p>

<p align="center">
  <sub><code>Last updated: July 2026 · Built with ❤️ from Brazil</code></sub>
  <br />
  <sub><code>EOF</code></sub>
</p>
