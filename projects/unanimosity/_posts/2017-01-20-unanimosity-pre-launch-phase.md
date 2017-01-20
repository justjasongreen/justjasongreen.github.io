---
title: "Unanimosity"
subtitle: "Pre-Launch Phase"
description: "A review of the Unanimosity pre-launch phase including the implementation of a pre-launch landing page"
image: "/assets/images/darts-target-bull-s-eye-delivering-37604.jpeg"
tags:
    - web-design
---

Despite a few unavoidable interruptions throughout the week, the first phase of the Unanimosity project is essentially complete, and the pre-launch landing page is LIVE! Check it out over at [unanimosity.github.io](https://unanimosity.github.io/){: target="_blank" }...

I say *"**essentially** complete"* because the *"FREE report"* promoted on the [home page](https://unanimosity.github.io/){: target="_blank" } hasn't actually been written yet. In one respect, this was a project management blunder on my part: the content for the "FREE report" that I had planned for the pre-launch phase is actually dependent on the successful implementation of certain components slated for completion in the second phase of the project (back-end systems). On the other hand, the marketing case for proceeding without having the actual report in place was a strong one: even if some subscribers unsubscribe when they are made aware that the report is not ready yet, I will still collect more subscribers than I would've by sending them to a blank "coming soon" page! Of course, this situation must be factored into the planning of the next phase of the project by giving a higher priority to those components necessary for the authoring of the report, specifically:

- The *data acquisition* library; and
- The *machine learning* library.

Funnily enough, this mirrors the natural implementation plan for the back-end phase of the project: the only other component to be implemented as part of that phase was the *worker process*, which depends on the *machine learning* library to operate, which in turn depends on the *data acquisition* library to function!

In terms of what has been implemented so far: the site itself is a [Jekyll](https://jekyllrb.com/){: target="_blank" rel="nofollow" } site hosted on [GitHub Pages](https://pages.github.com/){: target="_blank" rel="nofollow" }. Believe it or not, the site's development was started by cloning the the very same site that you are reading now, and cleaning out all the stuff that was specific to the [Just Jason Green]({{ '/' | relative_url }}) site, allowing me to focus on only the new functionality that was not relevant to my personal blog. The only noteworthy feature added to the [Unanimosity](https://unanimosity.github.io/){: target="_blank" } site was the [MailChimp](https://mailchimp.com/){: target="_blank" rel="nofollow" } integration, which was as simple as copying MailChimp's "naked sign up form" (a raw HTML version of the default sign up form for a given list) and pasting it into the relevant pages on the [Unanimosity](https://unanimosity.github.io/){: target="_blank" } site (with a little attention to [Bootstrap](http://getbootstrap.com/){: target="_blank" rel="nofollow" } styling enhancements, of course).

Moving forward, my time over the next week will be split between two tasks:

- Implementing the high priority components listed above;
- Driving traffic to the pre-launch landing page.

The need to get that report written gives a sense that the clock is ticking on getting those high priority components implemented, and I hope that that heightened sense of public accountability will act as a strong motivator to keep me focused on the task at hand. That said, if the implementation of those components takes less time than expected and I find myself with a little extra spare time in the next few days, I would like to write a blog post about the do's and dont's of pre-launch landing pages, because researching the essence of pre-launch landing pages was quite an insightful and educational experience for me! [Stay posted]({{ '/feed.xml' | relative_url }}) if such an article might interest you...
