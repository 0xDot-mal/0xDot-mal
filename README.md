# ✨Crxmson✨

```rust
const LANGUAGES: [&str; 5] = ["Rust", "C++", "JavaScript", "Python", "C"];

struct Skills {
    programming: Vec<String>,
    design: bool,
    problem_solving: bool,
}

impl Skills {
    fn new() -> Self {
        Skills {
            programming: Vec::new(),
            design: false,
            problem_solving: false,
        }
    }

    fn add_language(&mut self, lang: &str) {
        self.programming.push(lang.to_string());
    }
}

fn main() {
    let mut my_skills = Skills::new();

    for lang in LANGUAGES.iter() {
        my_skills.add_language(lang);
    }


    println!("My programming skills:");
    for lang in my_skills.programming.iter() {
        println!("  - {}", lang);
    }

  
    macro_rules! rahhh {
        () => {
            println!("This is a complex operation!");
        };
    }

    rahhh!();
}
```
<p align="left">
    <a href="https://www.youtube.com/channel/UC8haN0hOVjsV8FPpJBi4IFQ?sub_confirmation=1">
         <img alt="youtube subscribers" title="Subscribe to my YouTube channel" src="https://custom-icon-badges.demolab.com/youtube/channel/subscribers/UC8haN0hOVjsV8FPpJBi4IFQ?color=%23E05D44&label=SUBSCRIBE&logo=video&logoColor=white&style=for-the-badge&labelColor=CE4630"/></a> 
    <a href="https://www.youtube.com/channel/UC8haN0hOVjsV8FPpJBi4IFQ?sub_confirmation=1">
         <img alt="youtube views" title="YouTube views" src="https://custom-icon-badges.demolab.com/youtube/channel/views/UC8haN0hOVjsV8FPpJBi4IFQ?color=%23E1AD0E&logo=eye&logoColor=white&style=for-the-badge&labelColor=C79600"/></a> 
    <a href="https://github.com/0xDot-mal?tab=followers">
         <img alt="followers" title="Follow me on Github" src="https://custom-icon-badges.demolab.com/github/followers/0xdot-mal?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white"/></a>
    <a href="https://github.com/0xDot-mal?tab=repositories&sort=stargazers">
         <img alt="total stars" title="Total stars on GitHub" src="https://custom-icon-badges.demolab.com/github/stars/0xDot-mal?color=55960c&style=for-the-badge&labelColor=488207&logo=star"/></a>
</p>

<br>
<details> 
  <summary><h2>🛠️Tools I used somewhere🛠️</h2></summary>

  <h3>👨‍💻 Programming Languages include👨‍💻</h3>

  <p>
      <a href="https://github.com/search?q=user%3ADenverCoder1+language%3Aassembly"><img alt="MIPS Assembly" src="https://custom-icon-badges.demolab.com/badge/Assembly-525252.svg?logo=asm-hex&logoColor=white"></a>
      <img alt="Bash" src="https://img.shields.io/badge/Bash-121011.svg?">
      <img alt="C" src="https://custom-icon-badges.demolab.com/badge/C-03599C.svg?logo=c-in-hexagon&logoColor=white">
      <img alt="C++" src="https://custom-icon-badges.demolab.com/badge/C++-9C033A.svg?logo=cpp2&logoColor=white">
      <img alt="C#" src="https://custom-icon-badges.demolab.com/badge/C%23-68217A.svg?logo=cs2&logoColor=white">
      <img alt="CSS" src="https://img.shields.io/badge/CSS-1572B6.svg?logo=css3&logoColor=white">
      <img alt="Google Apps Script" src="https://custom-icon-badges.demolab.com/badge/Google%20Apps%20Script-02569B.svg?logo=gs&logoColor=white">
      <img alt="HTML" src="https://img.shields.io/badge/HTML-E34F26.svg?logo=html5&logoColor=white">
      <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?logo=javascript&logoColor=black">
  </p>


  <h3>🗄️Database and back-end etc..🗄️</h3>

  <p>
      <a href="#"><img alt="Node.js" src="https://img.shields.io/badge/Node.js-43853D.svg?logo=node.js&logoColor=white"></a>
      <a href="#"><img alt="Python" src="https://img.shields.io/badge/Python-14354C.svg?logo=python&logoColor=white"></a>
      <a href="#"><img alt="SQL" src="https://custom-icon-badges.demolab.com/badge/SQL-025E8C.svg?logo=database&logoColor=white"></a>
      <a href="#"><img alt="GitHub Pages" src="https://img.shields.io/badge/GitHub%20Pages-327FC7.svg?logo=github&logoColor=white"></a>
      <a href="#"><img alt="MongoDB" src ="https://img.shields.io/badge/MongoDB-4ea94b.svg?logo=mongodb&logoColor=white"></a>
      <a href="#"><img alt="MySQL" src="https://img.shields.io/badge/MySQL-00f.svg?logo=mysql&logoColor=white"></a>
      <a href="#"><img alt="SQLite" src ="https://img.shields.io/badge/SQLite-07405e.svg?logo=sqlite&logoColor=white"></a>
  </p>

  <h3>💻 Software and Tools</h3>

  <p>
      <a href="#"><img alt="Repl.it" src="https://img.shields.io/badge/Repl.it-0D101E.svg?logo=Replit&logoColor=white"></a>
      <a href="#"><img alt="Adobe" src="https://img.shields.io/badge/Adobe-FF0000.svg?logo=adobe&logoColor=white"></a>
      <a href="#"><img alt="Android" src="https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white"></a>
      <a href="#"><img alt="Audacity" src="https://img.shields.io/badge/-Audacity-0000CC?logo=audacity&logoColor=white"></a>
      <a href="#"><img alt="Bitwarden" src="https://img.shields.io/badge/-Bitwarden-175DDC?logo=bitwarden&logoColor=white"></a>
      <a href="#"><img alt="Dark Reader" src="https://img.shields.io/badge/-Dark%20Reader-141E24?logo=dark-reader&logoColor=white"></a>
      <a href="#"><img alt="Discord" src="https://img.shields.io/badge/-Discord-5865F2.svg?logo=discord&logoColor=white"></a>
      <a href="#"><img alt="Git" src="https://img.shields.io/badge/Git-F05033.svg?logo=git&logoColor=white"></a>
      <a href="#"><img alt="GitHub Desktop" src="https://img.shields.io/badge/GitHub%20Desktop-8034A9.svg?logo=github&logoColor=white"></a>
      <a href="#"><img alt="Google Sheets" src="https://img.shields.io/badge/Sheets-34A853.svg?logo=google%20sheets&logoColor=white"></a>
      <a href="#"><img alt="OBS Studio" src="https://img.shields.io/badge/-OBS-302E31?logo=obs-studio&logoColor=white"></a>
      <a href="#"><img alt="SonarLint" src="https://img.shields.io/badge/-SonarLint-CB2029?logo=sonarlint&logoColor=white"></a>
      <a href="#"><img alt="Stack Overflow" src="https://img.shields.io/badge/-Stack%20Overflow-FE7A16?logo=stack-overflow&logoColor=white"></a>
      <a href="#"><img alt="Visual Studio Code" src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?logo=visual-studio-code&logoColor=white"></a>

  </p>

   <h3>🪟Operation system🐧</h3>
   <p>
      <a href="#"><img alt="Windows 11" src="https://img.shields.io/badge/Windows%2011-1793D1.svg?logo=windows-11&logoColor=white"></a>
      <a href="#"><img alt="Windows 10" src="https://img.shields.io/badge/Windows%2010-1793D1.svg?logo=windows-10&logoColor=white"></a>
      <a href="#"><img alt="Arch Linux" src="https://img.shields.io/badge/Arch%Linux-1793D1.svg?logo=arch-linux&logoColor=white"></a>
      <a href="#"><img alt="Windows 11" src="https://img.shields.io/badge/Manjaro%Linux-1793D1.svg?logo=manjaro&logoColor=white"></a>
  </p>
</details>
<br>

<details> 
<summary><h2>📊My Stats📊</h2></summary>

<img align="center" src="https://github-readme-stats.vercel.app/api?username=0xDot-mal&show_icons=true&include_all_commits=true&theme=date_night&hide_border=false" alt="Crxmson's github stats"/>
<img align="center" alt="Crxmson's github stats" src="https://github-readme-stats.vercel.app/api/top-langs/?username=0xDot-mal&layout=compact&theme=date_night&hide_border=false"/>


</details> 
<details>
<summary><h2>⚒️Top Repositories⚒️</h2></summary>    
<a href="https://github.com/0xDot-mal/Grass-bot">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=0xDot-mal&repo=Grass-bot&theme=date_night"/>
</a>
<br><br>
<a href="https://github.com/0xDot-mal/Website-back-end">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=0xDot-mal&repo=Website-back-end&theme=date_night"/>
</a>
<br><br>
<a href="https://github.com/0xDot-mal/Counting-program">
<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=0xDot-mal&repo=Counting-program&theme=date_night"/>
</a>
</details>
<details>
<summary>
<h2>🌐My <a href="https://crxmson.netlify.app"  target="_blank">Website</a>🌐 & <a href="https://guns.lol/grxss"  target="_blank">Bio</a></h2>


</summary>
</details>

