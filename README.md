# GitHub Classroom alternatives

GitHub retired GitHub Classroom on 28 August 2026 ([changelog](https://github.blog/changelog/2026-08-27-github-classroom-deprecated)); new sign-ups had stopped on 26 May 2026 ([changelog](https://github.blog/changelog/2026-05-26-github-classroom-sign-ups-are-no-longer-available)). This is a list of what teachers can use instead, with what each option says about itself and a link to where it says it.

Facts were read on the date given in each section. Prices change; check the source before you decide. Corrections and additions are welcome as pull requests or issues.

## Contents

- [What to compare](#what-to-compare)
- [Stays on GitHub](#stays-on-github)
- [Hosted platforms](#hosted-platforms)
- [Open source, self-hosted](#open-source-self-hosted)
- [Inside Moodle](#inside-moodle)
- [What a class of 30 costs](#what-a-class-of-30-costs)
- [No longer available](#no-longer-available)
- [Moving your data out of GitHub Classroom](#moving-your-data-out-of-github-classroom)

## What to compare

- **Do students need a GitHub account?** Some options keep everything on GitHub, others do not need it at all.
- **Is there a coding environment?** Some give every student an editor and terminal in the browser; others only collect and grade code written elsewhere (on the student's machine, or in GitHub Codespaces).
- **Autograding:** which languages, and whether tests can be hidden from students.
- **LMS:** whether it runs inside an LMS such as Moodle, Canvas, Brightspace or Blackboard (LTI 1.3) and sends grades back to the gradebook.
- **Who runs it:** a vendor, your IT department, or you.
- **Cost:** per student, per course or per instructor, and what the free tier leaves out.

## Stays on GitHub

*Read 22 October 2026.*

- **[Classroom 50](https://github.com/foundation50/classroom50)**: free and open source, from the Fifty Foundation, the nonprofit behind Harvard's CS50. Assignments live in your GitHub organisation and are autograded with GitHub Actions; there is a web app and a command line. Needs an organisation on GitHub's Team or Enterprise plan, which GitHub Education gives verified educators free. One of the two partners GitHub named ([announcement](https://github.com/orgs/community/discussions/196615)). No coding environment of its own: students use their own machines or GitHub Codespaces.

## Hosted platforms

*Alphabetical. Read 22–23 October 2026.*

- **[Codio](https://www.codio.com/pricing)**: the commercial partner GitHub named. Courseware, coding environments in the browser, autograding, and LMS sign-in with grade passback. Free for instructors to build and explore; institutions agree pricing with Codio.
- **[CodeGrade](https://www.codegrade.com/pricing)**: grading for coding assignments, with a browser editor and a GitHub integration. Free for up to 50 students per course; LMS integration with grade sync is on paid plans.
- **[Gradescope](https://guides.gradescope.com/hc/en-us/articles/22254107840909)** (Turnitin): programming assignments with a configurable autograder (any language, via a setup script) plus rubric grading. Students can submit by upload or from a GitHub or Bitbucket repository. Many universities already hold an institutional licence; pricing is on request.
- **[Uppcoder](https://portal.uppcoder.com/github-classroom-alternative)**: a lab in the browser for every student (VS Code or JupyterLab and a terminal), autograded hand-ins (Python, Java, Go, Rust, C/C++) with public and hidden tests, rubrics and teaching assistants, Moodle, Canvas and Brightspace over LTI 1.3 with grades to the gradebook. Students do not need a GitHub account; courses can stay in the school's own GitHub organisation. Priced per educator ([pricing](https://portal.uppcoder.com/pricing)). Example assignments: [Python](https://github.com/websson/python-autograded-assignment), [Java](https://github.com/websson/java-autograded-assignment); [step-by-step guide](https://portal.uppcoder.com/guides/autograde-python-canvas-moodle).

## Open source, self-hosted

*Alphabetical. Read 23 October 2026.*

- **[Autolab](https://github.com/autolab/Autolab)**: course management with autograded programming assignments, gradebook, late penalties, grace days and cheat checking. Started at Carnegie Mellon, open source since 2014. A Rails web app plus a separate grading server (Tango).
- **[GitLab Classrooms](https://gitlabpages.univ-lille.fr/gitlab-classrooms/gitlab-classrooms/)**: a community project from the University of Lille that does for GitLab what GitHub Classroom did for GitHub: groups per class, student repositories from templates, grades from imported test results. MPL 2.0. Check its maintenance status before relying on it.
- **[nbgrader](https://nbgrader.readthedocs.io/)**: assignments in Jupyter notebooks: one master copy, a student version generated without solutions, autograding by running the notebooks, manual grades and feedback in a web view. BSD-3-Clause. Usually run on a JupyterHub.
- **[PrairieLearn](https://docs.prairielearn.com/)**: homework, quizzes and exams with randomised questions scripted in Python, and student code run in a sandbox (C, C++, Java, Python and more). From the University of Illinois; open source, with paid hosting from PrairieLearn, Inc. ([about](https://www.prairielearn.com/about)).
- **[Submitty](https://github.com/submitty/submitty)**: submission and grading from RPI: automated tests in many languages, manual TA grading, late-day policies. BSD-3-Clause.

## Inside Moodle

*Read 23 October 2026.*

- **[CodeRunner](https://moodle.org/plugins/qtype_coderunner)**: a Moodle question type: students write code in a quiz question and it is run against tests. Student code should run on a separate sandbox server, not the Moodle server.
- **[Virtual Programming Lab (VPL)](https://vpl.dis.ulpgc.es/)**: a Moodle activity for full programming assignments: an editor in the browser, running and testing submissions, similarity checks between submissions, dozens of languages. GPL. Needs its own execution server (VPL-Jail-System).

## What a class of 30 costs

*Published prices read 22 October 2026, for one course of 30 students. Check each source; currencies as published.*

| Option | What it costs | Source |
|---|---|---|
| Classroom 50 | Free. No coding environment; with GitHub Codespaces: $0.18/hour on 2 cores plus $0.07 per GB-month, about $108 a month in compute for 30 students at 20 hours each | [Codespaces billing](https://docs.github.com/en/billing/concepts/product-billing/github-codespaces) |
| Codio (higher education) | $48 per learner per semester or $90 per year: about $1,440 a semester for 30 | [codio.com/pricing](https://www.codio.com/pricing) |
| CodeGrade | Free up to 50 students per course; LMS grade sync on Advanced, $39 per student per course: $1,170 for 30 | [codegrade.com/pricing](https://www.codegrade.com/pricing) |
| Gradescope | Institutional licence, price on request | [gradescope.com](https://www.gradescope.com) |
| Uppcoder | Edu Educator €29 a month or €290 a year per educator, 3 labs of up to 30 students each | [portal.uppcoder.com/pricing](https://portal.uppcoder.com/pricing) |
| Autolab, nbgrader, PrairieLearn, Submitty, CodeRunner, VPL | Free software; you pay for the servers and the time to run them (PrairieLearn also sells hosting) | see each project |

## No longer available

- **GitHub Classroom**: retired 28 August 2026 ([changelog](https://github.blog/changelog/2026-08-27-github-classroom-deprecated)).
- **Replit Teams for Education**: shut down by Replit, announced in November 2023 ([The Register](https://www.theregister.com/2023/11/21/comp_sci_panic/)).

## Moving your data out of GitHub Classroom

GitHub's own guide to exporting rosters, assignments and grades: [Export or migrate GitHub Classroom data](https://docs.github.com/en/education/manage-coursework-with-github-classroom/get-started-with-github-classroom/export-or-migrate-github-classroom-data). The student repositories themselves stay in your organisation.

---

Maintained by people at [Websson](https://websson-doo.com), who build Uppcoder, one of the options above. We have tried to describe every option, ours included, in the same plain terms and only from its own published pages. If something here is wrong or missing, please open an issue or a pull request.
