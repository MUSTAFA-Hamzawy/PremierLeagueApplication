<div id="top"></div>
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#Screenshots">Screenshots</a></li>
    <li><a href="#Constraints">Constraints</a></li>
    <li><a href="#Contributors">Contributors</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
# About The Project
This application provides information and statistics about the players and managers of the premier league teams to make it easy for Supervisors of the premier league to manage it easily by employing coaches of teams and some other responsibilities that will be explained later. Each coach will have responsibilities that will be explained later. Also, we will help people who love football to know about their lovely teams and players.
<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Tools -->
# Built With

<img  src="https://raw.githubusercontent.com/MUSTAFA-Hamzawy/MUSTAFA-Hamzawy/main/logos/languages/c%23.svg" alt="C#" width="80" height="50"/> &nbsp;
<img  src="https://raw.githubusercontent.com/yurijserrano/Github-Profile-Readme-Logos/f994c418a134b58c4aec11152f6a4a33fa89da26/databases/mysql.svg" alt="MySql" width="80" height="50"/>
<img  src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="MS sql server" width="80" height="50"/> &nbsp;
<img  src="https://www.vhv.rs/dpng/d/523-5237557_visual-studio-logo-png-transparent-png.png" alt="VS" width="80" height="50"/> &nbsp;
<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Screenshots -->
# Screenshots
<div id="Screenshots">
  <img src="https://github.com/MUSTAFA-Hamzawy/PremierLeagueApplication/blob/master/Screen%20shots/intro%20page.jpeg" alt="intro-page" width="90%">
  <br><img src="https://github.com/MUSTAFA-Hamzawy/PremierLeagueApplication/blob/master/Screen%20shots/login%20form.jpeg" alt="login" width="90%">
  <br><img src="https://github.com/MUSTAFA-Hamzawy/PremierLeagueApplication/blob/master/Screen%20shots/reset%20pass.jpeg" alt="Reset password" width="90%">
  <br><img src="https://github.com/MUSTAFA-Hamzawy/PremierLeagueApplication/blob/master/Screen%20shots/sign%20up%20form.jpeg" alt="Sign up" width="90%">
  <p align="right">(<a href="#top">back to top</a>)</p>
  <br><img src="https://github.com/MUSTAFA-Hamzawy/PremierLeagueApplication/blob/master/Screen%20shots/WhatsApp%20Image%202022-07-26%20at%207.03.45%20PM.jpeg" alt="add player form" width="90%">
  <br><img src="https://github.com/MUSTAFA-Hamzawy/PremierLeagueApplication/blob/master/Screen%20shots/WhatsApp%20Image%202022-07-26%20at%207.03.46%20PM%20(1).jpeg" alt="" width="90%">
  <br><img src="https://github.com/MUSTAFA-Hamzawy/PremierLeagueApplication/blob/master/Screen%20shots/WhatsApp%20Image%202022-07-26%20at%207.03.46%20PM%20(2).jpeg" alt="dashboard" width="90%">
  <br><img src="https://github.com/MUSTAFA-Hamzawy/PremierLeagueApplication/blob/master/Screen%20shots/WhatsApp%20Image%202022-07-26%20at%207.03.46%20PM%20(3).jpeg" alt="" width="90%">
  <br><img src="https://github.com/MUSTAFA-Hamzawy/PremierLeagueApplication/blob/master/Screen%20shots/WhatsApp%20Image%202022-07-26%20at%207.03.46%20PM.jpeg" alt="" width="90%">
  <br><h2>Database Schema</h2>
  <br><img src="https://raw.githubusercontent.com/MUSTAFA-Hamzawy/PremierLeagueApplication/master/Screen%20shots/DB-Schema.png" alt="db-schema" width="90%">
  <p align="right">(<a href="#top">back to top</a>)</p>
  <br><h2>ER Model</h2>
  <br><img src="https://raw.githubusercontent.com/MUSTAFA-Hamzawy/PremierLeagueApplication/master/Screen%20shots/ER%20model.PNG" alt="ER-Diagram" width="90%">
 </div>
 
 <!-- Constraints -->
# Constraints
 
 |     Entity     |       Constraint       |     On Upadte     |     On Delete     |
|:-----------------:|:--------------:|:-----------------:|:--------------:|
|Coach|FK_Coach_team|No Action | No Action|
|Coach|FK_player_coach|Cascade|Set NULL|
|Manager|FK_Manger_team|No Action|No Action|
|Player|FK_player_coach|Cascade|Set NULL|
|Player|FK_player_team|Cascade|Set NULL|
|Supervisor_Assistant|FK_supervisor_assistant_supervisor|Cascade|Set NULL|

<!-- Contributors -->
# Contributors
<table id="Contributors">
  <tr>
     <td align="center"><a href="https://github.com/MUSTAFA-Hamzawy"><img src="https://avatars.githubusercontent.com/u/72188665?v=4" width="150px;" alt=""/><br /><sub><b>Mustafa Hamzawy</b></sub></a><br /></td>
     <td align="center"><a href="https://github.com/karimmahmoud22"><img src="https://avatars.githubusercontent.com/u/82693464?v=4" width="150px;" alt=""/><br /><sub><b>Karim Mahmoud<b/></td>
  </tr>
 </table>
  </div>
<p align="right">(<a href="#top">back to top</a>)</p>
