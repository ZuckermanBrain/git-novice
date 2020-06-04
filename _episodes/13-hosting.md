---
title: Hosting
teaching: 10
exercises: 0
questions:
- "Where should I host my version control repositories?"
objectives:
- "Explain different options for hosting scientific work."
keypoints:
- "Projects can be hosted on university servers, on personal domains, or on public forges."
- "Rules regarding intellectual property and storage of sensitive information apply no matter where code and data are hosted."
---

In addition to GitHub, there are several alternative ways of to host Git repositories.  We will only mention these alternatives in passing, since the workflows we've described in previous sections are specific to GitHub.  Alternate hosting providers are worth consideration for individuals using the command line version of Git, however, which is substantially more flexible than the GitHub Desktop interface.

One option is for the lab, the department, or the
university to provide a server, manage accounts and backups, and so on.  The
main benefit of this is that it clarifies who owns what, which is particularly
important if any of the material is sensitive (i.e., relates to experiments
involving human subjects or may be used in a patent application).  The main
drawbacks are the cost of providing the service and its longevity: a scientist
who has spent ten years collecting data would like to be sure that data will
still be available ten years from now, but that's well beyond the lifespan of
most of the grants that fund academic infrastructure.

Another option is to use a competing public hosting service like
[GitLab](https://gitlab.com),or
[BitBucket](https://bitbucket.org).
Similar to GitHub, these services also provide an intuitive web interface that enables people to create,
view, and edit their code repositories.  The downside of these services is that they do not have the same degree of popularity as GitHub, and as a result fewer scientists and programmers tend to use them except for specific use-cases or projects (i.e., GitHub benefits from network effects).  We currently do not recommend these competitors for these reasons.

For manuscript development in particular, platforms such as [Authorea](https://www.authorea.com/) or [Overleaf](https://www.overleaf.com/) provide a more manuscript-centric interface to Git, similar to a standard word processor.  Authorea deals well with multiple text formats (such as LaTeX and Markdown) while Overleaf is specific to manuscripts written in LaTeX.  As of writing (April 2020), OverLeaf requires a paid plan to include collaborators, whereas Authorea does not place a limit on the number of collaborators you can add to free tier plans.

With the exception of manuscript development, for which Authorea and Overleaf may be better options, we recommend remaining with GitHub for your Git repository hosting needs.  If you'd like to create a new repository, please consider locating it within the [Zuckerman Institute's GitHub organization](https://github.com/ZuckermanBrain) (more information about GitHub organizations can be found [here](https://help.github.com/en/github/setting-up-and-managing-organizations-and-teams/about-organizations)).  Contact research computing for further information about how to get started with adding your repository to this organization.
