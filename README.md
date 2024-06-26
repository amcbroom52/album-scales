<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#key-features">Key Features</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#deployment">Deployment</a>
      <ul>
        <li><a href="#test-user-login">Test User Login</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
Album Scales is a full-stack social web application that seamlessly integrates with Spotify's Web API, providing users with a platform to interact with Spotify's vast repository of music data. Designed to foster a community around music exploration and appreciation, Album Scales offers a range of features to enhance the user experience.

### Key Features
* **Rating System:** Post ratings for albums to share your opinions and contribute to the community's collective knowledge.
* **Album Information:** Access comprehensive information about specific albums, including ratings from users.
* **User Interaction:** Follow other users, view ratings from followed users, and search for users, albums, and artists.
* **Profile Management:** Edit your profile details to personalize your experience on the platform.
* **User Profiles:** Explore individual user profiles to see their information and all the ratings they have posted.

### Built With

* [![Python][Python]][Python-url]
* [![JavaScript][JavaScript]][JavaScript-url]
* [![Flask][Flask]][Flask-url]
* [![jQuery][jQuery]][jQuery-url]
* [![SpotifyAPI][Spotify]][SpotifyAPI-url]
* [![PostgreSQL][PostgreSQL]][PostgreSQL-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
To setup the development environment for Album Scales on your computer, follow the steps below:

### Installation
1. Get a free Spotify Web API client_id and client_secret at [Spotify Web API](https://developer.spotify.com/documentation/web-api/tutorials/getting-started)

2. Clone the repository
  ```sh
  git clone https://github.com/amcbroom52/album-scales.git
  ```
3. Create your venv
  ```sh
  python3 -m venv venv
  ```
4. Activate your venv
  ```sh
  source venv/bin/activate
  ```
5. Install the dependencies
  ```sh
  pip3 install -r requirements.txt
  ```
6. Create your database
  ```sh
  createdb album_rater
  ```
7. Create a .env file
  ```env
  CLIENT_ID = [YOUR SPOTIFY CLIENT_ID]
  CLIENT_SECRET = [YOUR SPOTIFY CLIENT_SECRET]
  SECRET_KEY = [SOME SECURE SECRET KEY]
  ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DEPLOYMENT -->
## Deployment

[Album Scales website](https://album-rater.onrender.com/)

### Test User Login

**Username:** testusername

**Password:** password

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Adrian McBroom - [LinkedIn](https://www.linkedin.com/in/adrian-mcbroom/) - adrianmcb2000@gmail.com

Project Link: https://github.com/amcbroom52/album-rater

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[PostgreSQL]: https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white
[PostgreSQL-url]: https://www.postgresql.org/
[JavaScript]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white
[JavaScript-url]: https://www.javascript.com/
[jQuery]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[jQuery-url]: https://jquery.com/
[Python]: https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[Flask]: https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white
[Flask-url]: https://flask.palletsprojects.com/en/3.0.x/
[Spotify]: https://img.shields.io/badge/Spotify_Web_API-1ED760?&style=for-the-badge&logo=spotify&logoColor=white
[SpotifyAPI-url]: https://developer.spotify.com/documentation/web-api
