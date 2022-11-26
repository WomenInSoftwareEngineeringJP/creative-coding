# 🐙 Session 7: GitHub Profile Customization

[GitHub](https://github.com/) is one of the most popular places for developers to showcase their portfolio online. Did you know that you can make your profile unique by editing a special repository? Let's dive in!

## How does it work?

Say your username is `github-coder`. If you create a new public repo with the same name as your username, e.g. `https://github.com/github-coder/github-coder`, this repo's `README.md` will be placed on your profile page at `https://github.com/github-coder` for everyone to see. The file uses [Markdown](https://www.markdownguide.org/), an open-source markup language that is popular with developers.\
\
A full guide is here:&#x20;

{% embed url="https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme" %}
Official Documentation on profile README
{% endembed %}

## That's great, but why does this matter?

GitHub is a place for storing code, but it's also a place to collaborate on projects, share your work, or even showcase your portfolio to land a new job. Let's take a look at some examples of unique GitHub profiles:

{% embed url="https://github.com/ann-kilzer" %}
This is the Author's profile, using Shields.io
{% endembed %}

{% embed url="https://github.com/BrunnerLivio/BrunnerLivio" %}
This one uses a style from 90s era internet
{% endembed %}

{% embed url="https://github.com/ari-hacks/ari-hacks" %}
This one features an animated gif and a minamalist layout
{% endembed %}

{% embed url="https://github.com/afc163" %}
This one is simple but whimsical
{% endembed %}

{% embed url="https://github.com/JessicaLim8/JessicaLim8" %}
This profile leverages GitHub actions to dynamically re-render a word cloud
{% endembed %}

{% embed url="https://github.com/kylepls#root" %}
This example uses anchor links to drive a Tic-Tac-Toe game
{% endembed %}

{% embed url="https://github.com/abhisheknaiidu/awesome-github-profile-readme" %}
More examples of unique profiles
{% endembed %}

## How do I get started?

### I want to use a template

If you're looking for something simple, or not confident about design, check out the following tools

{% embed url="https://rahuldkjain.github.io/gh-profile-readme-generator/" %}
Fill out the form and this tool will generate the markdown for you
{% endembed %}

{% embed url="https://reheader.glitch.me/" %}
Generates a header for a README file
{% endembed %}

### I want to design my own profile with components

#### Widgets (Badges, links, etc.)

{% embed url="https://shields.io/" %}
Customizable badges for GitHub and Open Source
{% endembed %}

{% embed url="https://github.com/Ileriayo/markdown-badges" %}
Pre-made Shields.io badges for Markdown
{% endembed %}

{% embed url="https://github.com/gautamkrishnar/blog-post-workflow" %}
Show your Blog Posts
{% endembed %}

{% embed url="https://github.com/teoxoy/profile-readme-stats" %}
GitHub Stats
{% endembed %}

{% embed url="https://github.com/rahul-jha98/github-stats-transparent" %}
Transparent Stats
{% endembed %}

{% embed url="https://github.com/lowlighter/metrics" %}
Unique Metrics templates
{% endembed %}

#### Images

{% embed url="https://www.seancdavis.com/posts/three-ways-to-add-image-to-github-readme/" %}

{% embed url="https://github.com/ann-kilzer/free-web-design-resources/blob/main/ASSETS.md" %}
References for stock photography, backgrounds, etc.
{% endembed %}

#### ASCII Art

{% embed url="https://patorjk.com/software/taag/#p=display&f=Graffiti&t=Type%20Something%20" %}

{% embed url="https://github.com/ajmeese7/readme-ascii" %}
ASCII style image generator
{% endembed %}

## Some (opinionated) advice on metrics

Many GitHub widgets focus a lot on metrics to measure output. These can be fun for some folks, but they notably don't measure quality, and sometimes conversations about GitHub commits are turned into an unreasonable measure. "Good developers" aren't measured in Lines of Code written, or commits per day.&#x20;

I once wrote a bot that backed up our build server's [Jenkins](https://www.jenkins.io/) configuration to GitHub every three hours. For security reasons, I created an isolated GitHub account with access to only one repo. The bot's commit history looked like a grid of uniform green. To the outside world, it might look like the perfect developer. But it was a mindless script running via [cron job](https://en.wikipedia.org/wiki/Cron). \
\
Remember that [commits can be gamed](https://devdojo.com/bobbyiliev/here-is-why-you-should-not-be-too-quick-at-judging-people-by-their-github-activity-stats), and it's normal to take breaks, have work / life balance, and don't get overly focused on numbers.

## Sources & Further Reading

* [https://github.com/rzashakeri/beautify-github-profile](https://github.com/rzashakeri/beautify-github-profile)
* [https://medium.com/nerd-for-tech/stand-out-by-personalizing-your-github-profile-f0a5d73f2b4d](https://medium.com/nerd-for-tech/stand-out-by-personalizing-your-github-profile-f0a5d73f2b4d)
