<h1 align="center"> DevFolio🌟</h1>
<p align ="center"><a href = "https://github.com/achaljhawar/DevFolio/graphs/contributors"><a href="https://github.com/achaljhawar/DevFolio/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/achaljhawar/DevFolio"></a><a href="https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fachaljhawar%2FDevFolio"><img alt="Twitter" src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2F"></a><a href="https://github.com/achaljhawar/DevFolio/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/achaljhawar/DevFolio"></a><img src="https://img.shields.io/badge/awesomeness-extreme-green"><a href = "https://discord.gg/YRm6nn8"><img alt="Discord" src="https://img.shields.io/discord/758269170151587852"></a><a href = "https://github.com/achaljhawar/DevFolio/blob/master/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/achaljhawar/DevFolio?style=flat-square"></a><a href="https://achaljhawar.github.io/DevFolio/"><img alt="Website" src="https://img.shields.io/website?url=https%3A%2F%2Fachaljhawar.github.io%2FDevFolio%2F"></a><br></p>
<br />

##  A minimal portfolio template for Developers!
## Built in:

- **HTML5**
- Pure **CSS3**
- Bit of **JavaScript**

## Features

⚡️ Modern UI Design + Reveal Animations\
⚡️ One Page Layout\
⚡️ Fully Responsive\
⚡️ Valid HTML5 & CSS3\
⚡️ Well organized documentation


You can add more things to make it even cooler! The comments in the code will help you navigate through it. Have a nice day! :D
[Demo Example](https://achaljhawar.github.io/DevFolio/)

## Sections

✔️ About me and summary\
✔️ Contact Info\
✔️ Projects

## Getting Started 🚀

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## How To Use 🔧

From your command line, first clone DevFolio:

```bash
# Clone this repository
$ git clone https://github.com/richards-isaac/DevFolio

# Go into the repository
$ cd DevFolio

# Remove current origin repository
$ git remote remove origin
```

## Template Instructions:

Go to `/index.html` and fill your information, there are 3 sections:

### Home Section

- Add your Name and a short description about yourself
- Add your social media links

```html
<div id="home">
  <div class="filter"></div>
  <section class="intro">
    <h3>
      Your Name
      <hr />
    </h3>
    <p>Short Description.</p>
    <p>Something more about yourself.</p>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
    <!--────social media links─────-->
    <div class="social-media">
      <a href="#" target="_blank"><i class="fab fa-codepen"></i></a>
      <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
      <a href="#" target="_blank"><i class="fab fa-github"></i></a>
      <a href="#" target="_blank"><i class="fab fa-linkedin-in"></i></a>
      <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
    </div>
  </section>
</div>
```

### Projects Section

- Add your short description ,the image of your projects and their links you can change the number of projects. You have two cards types, whit image and whitout image. Remember that cards aren't just for projects, you can use for work experiences, blogpost or whatever.

```html
<div id="projects">
             <h2>
               My Projects
               <hr />
             </h2>
             <p>Here are some of my projects, you may like.</p>
             <div class="work-box">
               <div class="work">
    <!--───────────────card───────────────-->
            <div class="card">
                <figure>
                  <img class="work-img" src="https://images.unsplash.com/photo-1462642109801-4ac2971a3a51?ixlib=rb-1.2.1&auto=format&fit=crop&w=1266&q=80">
                </figure>
                <div class="work-content">
                  <h3 class="work-title">Project Title</h3>
                  <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                  tempor incididunt ut labore et dolore magna aliqua.
                  </p>
                  <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                </div>
                  </div>
            <div class="card">
              <figure>
                  <img class="work-img" src="https://images.unsplash.com/photo-1462642109801-4ac2971a3a51?ixlib=rb-1.2.1&auto=format&fit=crop&w=1266&q=80">
                </figure>
                <div class="work-content">
                  <h3 class="work-title">Project Title</h3>
                  <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                  tempor incididunt ut labore et dolore magna aliqua.
                  </p>
                  <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                </div>
                  </div>
                  <div class="card">
              <figure>
                  <img class="work-img" src="https://images.unsplash.com/photo-1462642109801-4ac2971a3a51?ixlib=rb-1.2.1&auto=format&fit=crop&w=1266&q=80">
                </figure>
                <div class="work-content">
                  <h3 class="work-title">Project Title</h3>
                  <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                  tempor incididunt ut labore et dolore magna aliqua.
                  </p>
                  <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                </div>
                  </div>

            <!-- Simple Card for projects, work experiences or whatever -->

                  <div class="simple-card">
                <h3 class="work-title">Project Title</h3>
                <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua.
                </p>
                <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                  </div>    
                  <div class="simple-card">
                <h3 class="work-title">Project Title</h3>
                <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua.
                </p>
                <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                  </div>    
                  <div class="simple-card">
                <h3 class="work-title">Project Title</h3>
                <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua.
                </p>
                <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                  </div>    
                  <div class="simple-card">
                <h3 class="work-title">Project Title</h3>
                <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua.
                </p>
                <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                  </div>    
            </div>
          </div>
        </div>
```

### Contact Section

- Add your social media links

```html
<div id="contact">
  <!--────social media links─────-->
  <h3>
    Contact.
    <hr />
  </h3>
  <p>Feel free to contact me on my social media.</p>
  <div class="social-media">
    <a href="#" target="_blank"><i class="fab fa-codepen"></i></a>
    <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
    <a href="#" target="_blank"><i class="fab fa-github"></i></a>
    <a href="#" target="_blank"><i class="fab fa-linkedin-in"></i></a>
    <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
  </div>
</div>
```

## Deployment 📦

Once you have done with your setup. You need to put your website online!

I highly recommend to use [Github Pages](https://pages.github.com/) to achieve this on the EASIEST WAY.


## 🤝 Contributing <a href = "https://discord.gg/YRm6nn8"><img alt="Discord" src="https://img.shields.io/discord/758269170151587852"></a>

Any idea on how we can make this more awesome ? [Open a new issue](https://github.com/richards-isaac/DevFolio/issues)! We need all the help we can get to make this project awesome! You can also join the discord server to give suggestions.

## Contributors ✨

<table>
  <tr>
    <td align="center"><a href="https://github.com/shadowtime2000"><img src="https://avatars1.githubusercontent.com/u/66655515?s=180&v=4" width="100px;" alt=""/><br /><sub><b>Shadowtime2000</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/gasparnd"><img src="https://avatars3.githubusercontent.com/u/36377522?s=180&u=3b1f554c19b5dc2e21bf0aef269f44ee5bf87fdf&v=4" width="100px;" alt=""/><br /><sub><b>Gaspar Dolcemascolo</b></sub></a><br /></td>
  </tr>
</table>

### Don't forget to ⭐ and 🍴 the repository and share it with others.

## Stargazers ✨

Thanks goes to these wonderful people.

<table>
  <tr>
    <td align="center"><a href="https://github.com/SeraphicWolf"><img src="https://avatars1.githubusercontent.com/u/29392808?s=180&u=6bbb90ea2fa3549f6e63e266550084fd6b20fcff&v=4" width="100px;" alt=""/><br /><sub><b>Sebastian</b></sub></a><br /></td>
   
</table>

## References 👏🏻
- Some Design and Implementation Ideas are taken from <a href="https://repl.it/talk/templates/Portfolio-Site-Template/37272">Lilykhan's Portfolio Site Template</a> made for repl.it template jam.
