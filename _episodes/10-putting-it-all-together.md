---
title: Putting It All Together
teaching: 5
exercises: 0
questions:
- "What does a typical Git workflow look like?"
objectives:
- "Walk through a typical Git workflow with concepts learned in previous sections."
keypoints:
- "The concepts described in previous sections all contribute to a typical version control workflow."
---

Now let's see how all of the concepts described in previous sections cohere with a brief analogy:

Josh and Sarah are scientists that were working on a joint project. When the time came to write a paper for the project, Josh wrote a first sketch and opened a repository named `Nobel-Prize-Paper` within the [ZuckermanBrain](https://github.com/ZuckermanBrain) GitHub organization. They split the writing work between each other- Sarah would write the introduction and discussion sections while Josh would write the methods and results sections.

Sarah opened a `sarah-part` **branch** and Josh opened a `josh-part` **branch**. They **cloned** the branches to their local computers and worked. From time to time, they **added** (by staging) and **committed** their work to their local branches. Each time they felt that one of the paragraphs got to a reasonable level of completeness they **pushed** it into their remote branch. After a while Sarah and Josh **merged** their branches into the remote `master` branch and deleted the `josh-part` and `sarah-part` branches.  

They then had the first full version of the paper but it needed to be improved. Sarah created a `sarah-version` branch and Josh made a `josh-version` branch. Each of them worked on the entire paper to fine tune their draft. Josh merged his branch first and therefore had no conflicts with the current master version. When Sarah tried to merge, she found out that she needed to **pull** from `master` and resolve the conflicts before **merging** her version. 

Afterwards, since there were just small changes to be made to the paper Sarah and Josh worked directly on the `master` branch. Each of them switched to the `master` branch on their local repository. Now before **pushing** their commits they needed to **pull** from the `master` branch and resolve conflicts if they existed. 

Lea is an outside colleague who is on friendly terms with Josh and Sarah.  Because of this, they sent the paper to Lea to go over (and be acknowledged in the paper) she worked on her own branch and opened **pull request**  for the changes she offered. When everyone was happy with the version they **tagged** it with the name `Nature-Submission`, exported a PDF with [pandoc](https://pandoc.org/), and submitted it to Nature.

The operations for a typical Git workflow are illustrated as follows:

![Illustration of All Components in Git Workflow]({{ page.root }}/fig/git-workflow.svg)
