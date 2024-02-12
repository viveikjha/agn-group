---
layout: post
title: Welcome to the group
subtitle: We extend our greetings to the newly joined people.
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
author: Vivek Kumar Jha
---

### Hello everyone!

Active Galactic Nuclei (AGN) and its related fields are subjects of dynamic research in our country. The research activities are spread all over the country in various institutions, universities and colleges.  We look forward to building a community of Indian Astronomical Researchers working on AGN, with the aim of enhancing discussions and scientific collaborations. This idea was put forward during the panel discussion on 'AGN research in India' during the 9th Southern Regional Astronomy Meeting held at Manipal Academy of Higher Education, Karnataka. A student group was formed during the meeting to coordinate the formation of this nation-wide community.
A few programs we intend to do are:

1. Formation of a mailing group.
2.  Building a repository of researchers with their expertise details.
3. Weekly/biweekly paper discussions by young researchers.
4. A website with useful links to various tools, books, and lectures.
5. Promoting knowledge sharing through online platforms.  
6. Any other new ideas are welcome!!

This Google form is being circulated as a part of collecting the data for the same. We request you to kindly fill up the form at the earliest, giving in all relevant details. Looking forward to your active participation!
Contact the team below for any queries.

1. Dr. Vivek Kumar Jha, Manipal Academy of Higher Education, Karnataka - vivekjha.aries@gmail.com
2. Akhila K, Providence Women's College, Calicut, Kerala -  akhilasadanandan@gmail.com
3. Amal Abdulrahman, Farook College (Autonomous), Calicut, Kerala - amalar.amal@gmail.com


**Here is some bold text**

## Here is a secondary heading

[This is a link to a different site](https://deanattali.com/) and [this is a link to a section inside this page](#local-urls).

Here's a table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

How about a yummy crepe?

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
