---
title: "Hugo Website Setup"
discription: ""
datestring: 01/04/202
draft: false
tags: ["hugo", "website", "computer vision"]
cover: 
    image: images/hugo.PNG
---



I recently built my first website using [Hugo](https://gohugo.io/) — a lightning-fast static site generator. Here's a simple step-by-step guide on how I did it. If you're just getting started, this should help you get your first Hugo site up and running in no time!


## 1. 🧱 Install Hugo

First, you’ll need to [install Hugo](https://gohugo.io/getting-started/installing/). You can follow the instructions on the official site for your operating system.

---

## 2. 🌱 Create a New Website

Run the following command to create a new Hugo site (replace `MyFreshWebsite` with your desired name):

```bash
hugo new site MyFreshWebsite --format yaml
```

This sets up the project with YAML configuration.

---

## 3. 🎨 Install the PaperMod Theme

I chose the popular [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme for a clean and minimal look.

Navigate to your website directory and run:

```bash
git clone https://github.com/adityatelange/hugo-PaperMod themes/PaperMod --depth=1
cd themes/PaperMod
git pull
```

---

## 4. ⚙️ Set the Theme in Configuration

Go back to the root directory of your site and set the theme in your `hugo.yml` file:

```yaml
theme: ["PaperMod"]
```

---

## 5. 🖥️ Run Your Hugo Website

At this point, you can run your Hugo site to see it in action (even without content):

```bash
hugo server
```

---

## 6. ✍️ Create Your First Post

To create your first post, use:

```bash
hugo new posts/how2hugo.md
```

This creates a Markdown file in the `content/posts/` directory.

---

## 7. 📝 Edit Your Post

Open the `how2hugo.md` file in your favorite editor, copy and paste these steps (or write your own), and save it.

---

## 8. 🚧 View Your Draft Post

To view your site with draft content, run:

```bash
hugo server -D
```

Or, use:

```bash
hugo server -O
```

This opens the site directly in your browser.

