<link href="https://fonts.googleapis.com/css2?family=Fira+Code&display=swap" rel="stylesheet">

<style>
  body {
    font-family: 'Fira Code', monospace;
  }
  .glitch {
    font-family: 'Fira Code', monospace;
    color: #f00;
    position: relative;
    display: inline-block;
  }
  .glitch::before,
  .glitch::after {
    content: attr(data-text);
    position: absolute;
    left: 0;
    width: 100%;
    overflow: hidden;
    color: #0ff;
    clip: rect(0, 900px, 0, 0);
  }
  .glitch::before {
    animation: glitchTop 1.5s infinite linear alternate-reverse;
  }
  .glitch::after {
    animation: glitchBot 1.5s infinite linear alternate-reverse;
    color: #f0f;
  }
  @keyframes glitchTop {
    0% { clip: rect(0, 9999px, 0, 0); }
    10% { clip: rect(10px, 9999px, 25px, 0); }
    20% { clip: rect(5px, 9999px, 40px, 0); }
    100% { clip: rect(0, 9999px, 0, 0); }
  }
  @keyframes glitchBot {
    0% { clip: rect(0, 9999px, 0, 0); }
    10% { clip: rect(40px, 9999px, 70px, 0); }
    20% { clip: rect(15px, 9999px, 30px, 0); }
    100% { clip: rect(0, 9999px, 0, 0); }
  }
</style>

<div align="right">
  <img src="https://i.pinimg.com/736x/53/bf/53/53bf53eb8b91d0990ddc32cbc30becee.jpg" width="400px" alt="Mr. Robot banner"/>
</div>

---

<h3 class="glitch" data-text="> whoami">&gt; whoami</h3>

---


```sh
$ echo "Hello, friend."
Hello, friend.

$ ./Marawan --info
> System.out.println("CS Student at Nahda University");
> Status: Deconstructing corporate firewalls and building the new world on the ashes of the old.
> Mission: Find the exploits in the system. Are you a 1 or a 0?
$ ls -l /skills
# LANGUAGES
-rwx--x--x 1 user root 4096 JUN 10 18:47 Python
-rwx--x--x 1 user root 4096 JUN 10 18:47 C++
-rwx--x--x 1 user root 4096 JUN 10 18:47 MySQL
-rwx--x--x 1 user root 4096 JUN 10 18:47 PHP
-rwx--x--x 1 user root 4096 JUN 10 18:47 HTML5 & CSS

# OTHER
-rwx--x--x 1 user root 4096 JUN 10 18:47 Linux
-rwx--x--x 1 user root 4096 JUN 10 18:47 Microsoft Office
> executing payload...
<p align="center"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExd2k2Nm1hY3F1ODdxa3Fqd3pmNzRwZDRtZHVkZWhzY2J2dzl2OWllbCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/xT9IgzoKnwFNmISR8I/giphy.gif" width="400"/> </p>
> system logs
<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=Marawan6&show_icons=true&theme=radical" alt="GitHub stats"/> <img src="https://github-readme-streak-stats.herokuapp.com/?user=Marawan6&theme=radical" alt="GitHub streak"/> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Marawan6&layout=compact&theme=radical" alt="Top languages"/> </p>
> find_me
$ find /socials -type link
📫 Email     : marawan.othman06@gmail.com
🔗 LinkedIn  : https://www.linkedin.com/in/marawan-mohamed-652517320
> logs/end
<p align="center"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2F3anFiMnFzNndhZTVidjEyZTU4cnprY3VmZGxjYzE2NDAxMGZscCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/3ov9jExd1X1c3z3P8w/giphy.gif" width="400" alt="Hacker-style outro"/> <br/> <code>#PowerToTheUsers</code> </p> ```
