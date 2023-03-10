# <center>How to host a resume on Github Pages<center>

## What is this README?

This README describes the steps on how to host and format a resume using Markdown, a Markdown editor, GitHub Pages and Jekyll. These are the most common and popular software stacks.

I took inspiration from Andrew Etter by reading his book _Modern Technical Writing_. His book helped me ensure my README acts in accordance to the general principles of technical writing.
> According to Etter, documentation as such should be open-source and be written with an aim for other people to contribute to it.

This book goes in great detail and serves as a great source of knowledge for technical writing. I have included the link to the book under the [Additional resources](#Additional-resources) section.

---

## Requirements and necessities
Below are the some of the things you would require before proceeding:
   1. A resume that is in Markdown format.
   2. Jekyll alkready installed on your system.
   3. A Github account.

> In Modern Technical Writing, Etter emphasizes on using Markdown and AsciiDoc, which are Lightweight Markup Languages. This is because they are fairly easy to learn for beginners and are user friendly since they can be read in their raw format too. 

I have included links that will guide you with learning Markdown, Github, and a Jekyll installation primer in the [Additional resources](#Additional-resources) section.

## Instructions
### 1) Searching for (the static) theme of your website.  
After learning how to use Markdown and Github, or after completing the videos provided, you can now start looking for a static theme for your website. Github pages and Jekyll will aid you with this.

While writing this README, I came across a website with some Jekyll themes I found intriguing. If you would like to take a look, I have added their links too under [Additional resources](#Additional-resources).

> Furthermore, we also learn from Etter's book that static websites are robust since they can be very easy to setup, are competent in terms of speed, and are efficient in terms of security. They can be hosted anywhere, as they do not have any server-side application. Also, not having to install anything or having a adatabse makes it even easier to move your directory.

### 2) Forking your repository.   https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks
> From a page on Github about [forks](#https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks), I learnt that when you fork your repository, you are simply creating another copy of it in your profile, and when you make changes to this copy, it does not affect the original repository.                         

  1.  After you select your desired theme, click on repository option provided. This will take you to it's Github repository.
  2.  Once you are taken to your Github account, select the _Fork_ tab which is usually located at the top right of the webpage. 
  3.  Next, select your desired name for your repository. Note that you should ensure that the name follows the format _username.github.io_. Ensure the settings chosen are on default, and finally click on the _create_ fork_ tab.

### 3) Making edits/changes to your resume.
Throughout your career as a student or as an employee you will often have the requirement to make changes to your resume. I will show you how to do this here.
- The most important file to consider when modifying your resume is the _config.yml_ file. This is where you will make all your changes and save them in accordance. 
- After successfully forking your theme to your repository, under the _config.yml_ file, you can simply click on the pencil icon at the top which will allow you to modify your content. 
- Once you complete making your modifications, when you scroll down to the end of your file, you will see a tab that says _Commit changes_. Useful commit messages will be your best friend. Having good commit messages is considered good practice as you will be able to easily navigate all your changes.
- Your saved changes will then reflect on your static website.

> According to Etter, having a website for such work is considered useful so that you can easily control all of the changes being made. Commiting regularly ensures your website will remain up to date. 

### 4) How to view your static website.
You will now be able to successfully view your website. Github makes this even easier by generating a link to your website that you can use profusely.
- To navigate to the link, simply click on _settings_ (located under your repository name at the top), then go to _pages_ (found on the left) and finally Github Pages provides the link to you in the form _"https://username.github.io/".
- With the built in features of Github and Github Pages, andy changes made to your _config.yml_ file will automatically sync with your website, always keeping it up to date.

#### :smiley:Here is a visual gift since you made it this far!:smiley:
![](Resume.gif)

## Additional resources.
* A [Markdown tutorial](https://www.markdowntutorial.com/).
* You can purchase _Modern_ _Technical_ _Writing_ by Andrew Etter's on Amazon [here](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).
* Guide to installing [Jekyll](https://jekyllrb.com/docs/).
* An excellent source for [website themes](https://jekyll-themes.com/).


## Acknowledgements And Authors

- List of group members who assisted in making improvements to the README file: 
  1. Mia Battad
  2. Yirong Wang
  3. Jiehao Lai


##FAQ Section

...END...
