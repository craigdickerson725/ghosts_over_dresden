# [GHOSTS OVER DRESDEN](https://craigdickerson725.github.io/ghosts_over_dresden)

[![GitHub commit activity](https://img.shields.io/github/commit-activity/t/craigdickerson725/ghosts_over_dresden)](https://github.com/craigdickerson725/ghosts_over_dresden/commits/main)
[![GitHub last commit](https://img.shields.io/github/last-commit/craigdickerson725/ghosts_over_dresden)](https://github.com/craigdickerson725/ghosts_over_dresden/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/craigdickerson725/ghosts_over_dresden)](https://github.com/craigdickerson725/ghosts_over_dresden)

Welcome to the Ghosts Over Dresden Band Website!  The goal of this website is to serve as a site to both introduce the band to those unfamiliar with their music, and also to provide those who are already fans an outlet for listening to the entire discography and sign up for the mailing list.

The wish of the band was to use all original images (taken by band members and friends of the band alike) to draw the interest of those who are checking out the band for the first time.  Because the music appeals to the darkwave/post-punk genres, the style is purposely dark with a goth asthetic. 

![screenshot](documentation/mockup_screenshot.png)

source: [amiresponsive](https://ui.dev/amiresponsive?url=https://craigdickerson725.github.io/ghosts_over_dresden)

## UX

I began the design with a mobile-first approach in mind. I started with the homepage, using the Code Institute's 'Love Running' walkthrough project as a basis for getting the ball rolling.  However, since this is a website for a musical project, it was important to incorporate the music into the website.  For that reason, I chose to add a 'Music' page rather than a 'Gallery' page, as well as creating links so that clicking on the artwork takes the user to the YouTube page for the release clicked.

Of course, a band needs to keep a good relationship with their listeners, and be accessible to them.  For this reason, a Contact page was added with a signup form, so that the user can be notified anytime a new track, merch item, or live show date is released.  As most bands are currently making their announcements via social media platforms, the band and I did not find it necessary to expand the website, as they create the bulk of their multi-media content exclusively for their social media sites--which are linked in the footer of the webpage.

### Colour Scheme

Ghosts Over Dresden are a part of the 'goth' scene, so the color scheme was quite simple:  dark colors, with a black backgroud when applicable, and typically red or white text.  The photos/artwork was all created by professional artists who are a part of the band, and the colors they kept are typically dark, with mysterious images that appeal to fans of the gothic asthetic as well as the musical subcultures that are part of the goth scene.

- `rgb (0, 0, 0)` used for backgrounds when applicable.
- `rgb (255, 255, 255)` used for all home and music page text.
- `rgb (255, 0, 0)` used for contact form text.

### Typography

In considering fonts, it was important for the band to have something that looked both 'hand-written' as well as dark but elegant at the same time.  In reviewing many different fonts on Google Fonts, it was decided that the Amatic SC font was the best choice.  Therefore, [Amatic-SC](https://fonts.googleapis.com/css2?family=Amatic+SC:wght@400;700&display=swap) was used for all headers and titles.

## User Stories

### New Site Users

- As a new site user, I would like to see a cool, catchy graphic, so that I can get a feel for the vibe of the band.
- As a new site user, I would like to have a discography page that links to the band's releases, so that I can hear the music they are making.
- As a new site user, I would like to have a contact page, so that I can connect with the band and receive news concerning the band as it happens.

### Returning Site Users

- As a returning site user, I would like to easily find the complete discography, so that I can listen to the music that I have not yet heard.
- As a returning site user, I would like to easily find a way to contact the band, so that I can request live shows, merch, or anything that I feel should be made available to fans.
- As a returning site user, I would like to have quick access to the various social media pages for the band, as well as streaming platforms, so that I can see what the band is up to more immediately (ie, daily social posts, etc).

## Features

### Existing Features

- **Interactive Navigation Bar**

    - The Navigation Bar is set up to the upper right of the screen (opposite the header, which is set up on the right side) on large screens. There is a toggle option to show an underline beneath the page being highlighted by the mouse.

    ![screenshot](documentation/features/navbar_large_screens.png)

    -For mobile screens, the navbar is represented in the upper right corner of the screen by a candelabra when not activated.  When activated, the navigation menu drops down underneath the header.

    ![screenshot](documentation/features/navbar_mobile_unclicked.png)
    ![screenshot](documentation/features/navbar_mobile_dropdown.png)

- **Footer which provides quick links to the most popular social media pages, as well as most popular streaming platforms**

    - The footer appears at the bottom of each page and contains links to the most relevant and important social media/streaming platform pages of the band.  The links are interactive, and display the icons for Instagram, Spotify, Band Camp, and iMusic.  Clicking on the icons takes the user to the appropriate page.  For many users, this will be the most important feature of the page, as most fans in this time desire constant social media posts from bands to feel connected to them.

![screenshot](documentation/features/footer.png)

- **Music Page With Complete Discography which Connects to Each Release**

    - The music page is simple, but effective.  It displays the cover art for each of the band's releases.  Touching (for mobile screens) or clicking (for laptops/desktops) the artwork takes the user to the Youtube site for the release, so the user can hear the music.  

![screenshot](documentation/features/music_page_mobile.png)
![screenshot](documentation/features/music_page_large_screens.png)

-**Contact Page With Email Signup**

  - The contact page provides a signup form, so that the user can connect with the band.  All fields are required, so the information should be filled out completely or a message will inform the user to complete the info.  Also, a confirmation is given when the information is correctly submitted.

![screenshot](documentation/features/signup_form_with_info_incomplete.png)
![screenshot](documentation/features/signup_form_with_info_completed.png)
![screenshot](documentation/features/signup_form_submission_confirmation.png)

### Future Features

- ADD A NEWS PAGE FOR UPCOMING PROJECTS
    - The band are working on a full-length album, as well as booking gigs and creating merchandise.  When these things are ready, they wish to add a new page for News, which would be providing info on all the merch, upcoming music releases, and live shows.
- JUKEBOX ADDED TO MUSIC PAGE
    - When more music becomes available, it would be a nifty addition to have a 'jukebox' style player added to the music page.  This would contain every available song, all in one convenient place, available at one click.
- OPEN FORUM WHERE FANS CAN CHAT WITH THE BAND AND EACH OTHER
    - As the following for the band grows, it would be a great feature to provide a space for the fans to leave messages to the band, and for the band to respond.  Also, fans from different geographical locations could also connect and form new friendships.

## Tools & Technologies Used

- [![Markdown Builder](https://img.shields.io/badge/Markdown_Builder-grey?logo=markdown&logoColor=000000)](https://tim.2bn.dev/markdown-builder) used to generate README and TESTING templates.

- [![Git](https://img.shields.io/badge/Git-grey?logo=git&logoColor=F05032)](https://git-scm.com) used for version control. (`git add`, `git commit`, `git push`)

- [![GitHub](https://img.shields.io/badge/GitHub-grey?logo=github&logoColor=181717)](https://github.com) used for secure online code storage.

- [![Gitpod](https://img.shields.io/badge/Gitpod-grey?logo=gitpod&logoColor=FFAE33)](https://gitpod.io) used as a cloud-based IDE for development.

- [![HTML](https://img.shields.io/badge/HTML-grey?logo=html5&logoColor=E34F26)](https://en.wikipedia.org/wiki/HTML) used for the main site content.

- [![CSS](https://img.shields.io/badge/CSS-grey?logo=css3&logoColor=1572B6)](https://en.wikipedia.org/wiki/CSS) used for the main site design and layout.

- [![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-grey?logo=githubpages&logoColor=222222)](https://pages.github.com) used for hosting the deployed front-end site.

- [![Font Awesome](https://img.shields.io/badge/Font_Awesome-grey?logo=fontawesome&logoColor=528DD7)](https://fontawesome.com) used for the icons.

- [![ChatGPT](https://img.shields.io/badge/ChatGPT-grey?logo=chromatic&logoColor=75A99C)](https://chat.openai.com) used to help debug, troubleshoot, and explain things.

## Testing

> [!NOTE]  
> For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Deployment

The site was deployed to GitHub Pages. The steps to deploy are as follows:

- In the [GitHub repository](https://github.com/craigdickerson725/ghosts_over_dresden), navigate to the Settings tab 
- From the source section drop-down menu, select the **Main** Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://craigdickerson725.github.io/ghosts_over_dresden)

### Local Deployment

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://github.com/craigdickerson725/ghosts_over_dresden) 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash or Terminal
5. Change the current working directory to the one where you want the cloned directory
6. In your IDE Terminal, type the following command to clone my repository:
	- `git clone https://github.com/craigdickerson725/ghosts_over_dresden.git`
7. Press Enter to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/craigdickerson725/ghosts_over_dresden)

Please note that in order to directly open the project in Gitpod, you need to have the browser extension installed.
A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository.
You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/craigdickerson725/ghosts_over_dresden)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

### Local VS Deployment

There are no noticeable differences between the local and deployed page that I have found.

## Credits

### Content

| Source | Location | Notes |
| --- | --- | --- |
| [Markdown Builder](https://tim.2bn.dev/markdown-builder) | README and TESTING | tool to help generate the Markdown files |
| [Chris Beams](https://chris.beams.io/posts/git-commit) | version control | "How to Write a Git Commit Message" |
| [Tim Nelson](https://tim.2bn.dev/) | code snippets | shared code snippet variations to adjust syles on Homepage and Contact form images |
| [Code Institute](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LRFX101+5/courseware/e805068059af42af87681032aa64053f/8703311af8594e9d83c32a580cd97a14/) | Love Running Walkthrough Project | code for basic homepage, header, footer, and navbar structures, as well as for sign up form |
| [ChatGPT](https://chatgpt.com/) | various code stylings | code for adding video links to images |

### Media

The artwork for the entire website was all created by the band's members, and media team.  The Homepage images are by Luisa Aelig.  All other images on the site were created by Bea Keller, Cindy Wagner, and Quinn Buyck.

### Acknowledgements

- I would like to thank my Code Institute mentor, [Tim Nelson](https://github.com/TravelTimN) for his support (ie encouragement as well as code snippets, and for the extremely helpful readme and testing markdown builders) throughout the development of this project, and for making time outside of normal hours to help me...without him, this would not have been possible.
- I would like to thank the [Code Institute](https://codeinstitute.net) tutor team for their assistance with troubleshooting and debugging some project issues.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for the moral support; it kept me going during periods of self doubt and imposter syndrome.
- I would like to thank my wife Julia and daughter Serafina for their patience as I worked many hours to create this page.
- Of course, I want to thank Bea Keller, Cindy Wagner, Luisa Aelig, and Quinn Buyck for creating all original artwork to use in the creation of this project.  
