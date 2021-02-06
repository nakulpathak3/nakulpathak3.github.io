---
layout: post
title: "Star Wars"
date: 2020-02-06 14:43:02 -0500
categories: react, rails, learning
---

### Star Wars

I recently had to do a take-home interview assignment that was a Single-Page app offering a view for the Star Wars API. While I am generally against take-home assignments (whole other story), I liked the company and thought it would be a fun way to learn React, refresh my starting-Rails-projects-from-scratch skills, and have a good time.

### Learnings

React is hard as %$%$%, especially building a single-page-app. There's a lot of anti-patterns you can write (I have like 3 in my code right now 😅) and debugging isn't fun. I learned some state vs. props best practices, how React routing works, and that `console.log` is basically still the way to debug stuff since the last time I did front-end in detail (many years ago).

That said, React does allow you to DRY (Don't Repeat Yourself) things up really well and Chrome's React Extensions are a good debugging tool to inspect states and props.

I hadn't worked with Rails 6 much but honestly, the basics are all the same as 2015. One of the best things I found (not sure if this existed back in the day) is this -

```bash
$ rails new star-wars-api --webpack=react --database=postgresql
```

I loved the flags that let me setup react and PostgreSQL so easily. I actually realized this after I'd set up the app but I think this is great to know for future projects.

Overall, it was a fun experience. I should beautify the app but don't feel like writing CSS and there are other things I gotta learn/contribute to :)

### Code

https://github.com/nakulpathak3/star-wars-api.

### Deploy

Heroku is amazing for quick deploys of apps. I deployed mine at https://shielded-basin-88601.herokuapp.com/. I also left a little game in there for you if you can find it 😉 XOXO
