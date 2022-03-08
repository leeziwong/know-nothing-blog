---
title: 'Complete reading <A Complete Guide to useEffect>'
excerpt: 'Introducing a great article about React useEffect'
coverImage: '/assets/blog/cover-images-from-friend-david/hu-nan-zhang-jia-jie.JPG'
date: '2022-03-08T15:16:40.922Z'
author:
    name: lz
    picture: ''
ogImage:
    url: ''
---

In the article [A Complete Guide to useEffect](https://overreacted.io/a-complete-guide-to-useeffect/), [Dan Abramov](https://mobile.twitter.com/dan_abramov) gave a great deep dive introduction about the *useEffect* hook.

It gives me a more clear understand about functional component render, *effect* and how to use effect correctly.

Functional render makes a heavy use of javascript closure to capture component state.

Several key points of the article:

> - Don’t Lie to React About Dependencies
> - Two Ways to Be Honest About Dependencies
>   - Fix the dependency array to include all the values inside the component that are used inside the effect
>   - Making Effects Self-Sufficient

And many more well written introduction, you really should read the article.


