---
title: 'Programming test against use case and interface not coverage'
excerpt: 'A thought of writing unit and integration tests'
coverImage: '/assets/blog/cover-images-from-friend-david/hu-nan-zhang-jia-jie.JPG'
date: '2022-03-08T15:50:09.840Z'
author:
    name: lz
    picture: ''
ogImage:
    url: ''
---

Over the years, I have seen programmers writing unit or integration tests against coverage, and they are proud to have written 100% coverage code.

By the means to conveniently write test, they would break the interface of encapsulation:
- making private method to be protected inorder to directly test against that method
- testing component method (implementation) not the UI (interface)

That make me sad.

I think test against interface and use case would make you write better structure and more maintainable code, and maintainable tests.

While test breaking the interface of encapsulation just make things bad.



