---
title: Build a Blog in 10 Minutes with Gatsby
date: "2022-10-16T23:46:37.121Z"
---

Thanks to CuriousByte for their video on this topic. It was the “under 9 minutes” part that brought me in. I’m tired.

An overview of the tools we will be using:
- Gatsby
- Netlify
And, of course:
- npm
- Node.js
- Git

We will be making use of a pre-made starter template provided by thomaswangio on GitHub. Mighty clean and functional.

```console
sudo npm install -g gatsby@latest
```

If we already have Gatsby installed, let's check our version:
```console
gatsby -v
```

And if necessary, update:
```console
sudo npm install -g gatsby@latest
```

Let's navigate to our chosen project folder. For me, it's:
```console
cd Sites
```

Now we want to be able to talk to Gatsby. So let's install the Gatsby Command Line Interface:
```console
npm install -g gatsby-cli
```

Once that's done, we can create our new Gatsby project. To get up and running as fast as we want, let's grab thomaswangio's gatsby-personal-starter-blog from GitHub, and build our site from that:
```console
gatsby new techtrove https://github.com/thomaswangio/gatsby-personal-starter-blog
```

Whilst we're waiting, let's create a GitHub repository for our project.

And when our files are in order, push them to the master branch:
```console
cd techtrove
git:(master) gst
git:(master) git add -A && git commit -m "initial commit"
git:(master) git remote add origin https://github.com/bethxyz/techtrove.git
git:(master) git push
```

> Note: If you have Git-related issues with this part, see here for installing Git on your system or see Git docs.