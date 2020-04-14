---
title: Licensing
teaching: 5
exercises: 0
questions:
- "What licensing information should I include with my work?"
objectives:
- "Explain why adding licensing information to a repository is important."
- "Choose a proper license."
- "Explain differences in licensing and social expectations."
keypoints:
- "People who incorporate General Public License (GPL'd) software into their own software must make their software also open under the GPL license; most other open licenses do not require this."
- "The Creative Commons family of licenses allow people to mix and match requirements and restrictions on attribution, creation of derivative works, further sharing, and commercialization."
- "People who are not lawyers should not try to write licenses from scratch."
---

When a repository with source code, a manuscript or other creative
works becomes public, it should include a file named `LICENSE` or
`LICENSE.txt` in the base directory of the repository that clearly
states under which license the content is being made available. This
is because creative works are automatically eligible for intellectual
property (and thus copyright) protection. Reusing creative works
without a license is dangerous, because the copyright holders could
sue you for copyright infringement.

A license solves this problem by granting rights to others (the
licensees) that they would otherwise not have. What rights are being
granted under which conditions differs, often only slightly, from one
license to another.

Before you assign a license to the code or manuscript in your Git repository, verify that you hold the copyright and/or have the right to assign a license.  This step is often overlooked, but is essential to protect yourself from potential legal repercussions in the future.  For instance, the Bayes-Dole Act (see [here](http://ccnmtl.columbia.edu/projects/rcr/rcr_data/foundation/index.html#2_B)) stipulates that certain research products created with grant funding are generally owned by the university, rather than individual researchers.  Academic publishers also sometimes request that the copyright for manuscripts be transferred to them (see [here](https://en.wikipedia.org/wiki/Copyright_policies_of_academic_publishers)), though this is changing as open access journals gain traction.  

Columbia's policy on who owns the copyright for a work produced at the university can be found [here](http://www.columbia.edu/cu/provost/docs/copyright.html), and you can obtain general information from [Copyright Advisory Services](https://copyright.columbia.edu/).  The STAN Project, a major open source initiative in the department of statistics, has a detailed written account about the actions they took to ensure legal compliance [here](https://statmodeling.stat.columbia.edu/2016/08/28/copyright-and-licensing-basics-for-code-and-text/).

Once you've verified that you can assign a license, a few licenses are by far the most
popular, and [choosealicense.com](https://choosealicense.com/) could
help you find a common license that suits your needs.  Important
considerations include:

* Whether you want to address patent rights.
* Whether you require people distributing derivative works to also
  distribute their source code.
* Whether the content you are licensing is source code.
* Whether you want to license the code at all.

Choosing a license that is in common use makes life easier for
contributors and users, because they are more likely to already be
familiar with the license and don't have to wade through a bunch of
jargon to decide if they're ok with it.  The [Open Source
Initiative](https://opensource.org/licenses) and [Free Software
Foundation](https://www.gnu.org/licenses/license-list.html) both
maintain lists of licenses which are good choices.

[This article][software-licensing] provides an excellent overview of
licensing and licensing options from the perspective of scientists who
also write code.

At the end of the day what matters is that there is a clear statement
as to what the license is. Also, the license is best chosen from the
get-go, even if for a repository that is not public. Pushing off the
decision only makes it more complicated later, because each time a new
collaborator starts contributing, they, too, hold copyright and will
thus need to be asked for approval once a license is chosen.

> ## What licenses have I already accepted?
>
> Many of the software tools we use on a daily basis (including in this workshop) are
> released as open-source software. Pick a project on GitHub from the list below, or
> one of your own choosing. Find its license (usually in a file called `LICENSE` or
> `COPYING`) and talk about how it restricts your use of the software. Is it one of
> the licenses discussed in this session? How is it different?
> - [Git](https://github.com/git/git), the source-code management tool
> - [CPython](https://github.com/python/cpython), the standard implementation of the Python language
> - [Jupyter](https://github.com/jupyter), the project behind the web-based Python notebooks we'll be using
{: .challenge}

[software-licensing]: https://doi.org/10.1371/journal.pcbi.1002598
