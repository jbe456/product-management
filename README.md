# Product Management

Best product management know-how

## Product Development

- follow a Kanban-like agile methodology as much as possible, to lower the pressure on individuals and the temptation to botch devlopments. Do not be dogmatic about it.
- prioritize as much as possible:

  > “People think focus means saying yes to the thing you've got to focus on. But that's not what it means at all. It means saying no to the hundred other good ideas that there are. You have to pick carefully. I'm actually as proud of the things we haven't done as the things I have done. Innovation is saying ‘no’ to 1,000 things.”
  >
  > \- Steve Jobs

- be iterative as much as possible: each developoment should be broken down into tiny pieces that should be quick to implement and review. Use feature flag to help merging features sooner.
- give rythm via scheduled, regular release where all committed developments are in.
- spread key required developments across releases and plan those in advanced so that they are ready early in the release cycle.
- make a Release Candidate before the finl release with a specific trial period that can't be reduced if tests coverage are not good.
- must have:
  - do Code Reviews.
  - never test the main branch: enforce all tests and linting are passing before merging on the main branch.
  - have end-to-end tests and good unit/integration tests coverage.
  - deprecate anti patterns with linters as soon as they are spotted.
- developments should (from the least to the most complex):
  - meet technical & functional requirements
  - prevent regression via unit, integration and e2e tests
  - design architecture and use patterns that ease support & extendability
  - enfore design in the long term. Ex: separate packages to ensure code isolation

## UX

- a design session with written specifications must precede any written code
- include users in your design sessions

## Values

- **Challenge everything & inspire innovation through healthy discord**.

  The ability to speak freely, disagree with others’ opinions, and express one’s point of view each correlates strongly with how innovative the company is. The more people can speak up, the more groundbreaking the company’s progress.

- **The system must protect the individuals**.

  A bug introduced in the latest commit? this is because of a missing test. The tests were not run before merging the feature branch? A continuous integration build should be set up to prevent merging any branch without passing tests. An architecture anti-pattern has been committed? a linting rule should be set up to detect and prevent such pattern. Botching developments last minutes? review how planning is made. Developers staying late and swamped with work? this might be due to poor priorization or resource management. etc

  Think [poka-yoke](https://en.wikipedia.org/wiki/Poka-yoke).

## Team management

- meet with each individual of the team for 60 minutes every month with direct/honnest feedback from both sides. Take notes of each interview. This is probably the single most powerful tool available to improve people and processes and prioritize what to focus on next.
- favor [the ability to speak up freely over anonymous feedback](https://www.fastcompany.com/40518499/my-company-is-killing-anonymous-employee-feedback-heres-why): "Anonymity reinforces the idea that it’s risky to speak up.". Cf [Values](#values).
- organize post-mortem sessions on a regular basis to collectively share positive feedback and things to improve as well as ways to address those issues.
- foster safe environment where individuals help and trust each other: stealing work to achieve a deadline faster, help on merging a development...
- organize regular activities & outings with the team (bar, team lunch, climbing, bowling, laser tags...) sponsored or not to create a sense of camaraderie.
- job sculpt when possible: adapt task to each individual's strengths and desires.
- favor standard practices, patterns & tools as well as documentation for rapid & cheaper integration in a context of job hopping.
- provide transparency and document/share:
  - Roadmap: each team member's priority dev for next cycle.
  - Team's vacation and remote work.
  - HR common's questions: rules for working remotely, time off, traveling, expense, paperwork, visas...
  - Matrix skills detailing expected expertise and how to progress to the next level.

## Recruitment

- favor interview conditions that are as close as possible to real-life tasks: i.e. similar to what the candidates used or will use to develop. [Avoid whiteboards...](https://medium.com/javascript-scene/tech-hiring-has-always-been-broken-heres-how-i-survived-it-for-decades-b7ac33088de6)
- test candidates on how well they know what they pretend to know rather than how well they know what the interviewer knows. In other words, design the interview like a UX interview, with the end goal of testing how much candidates know their topics rather than asking questions to make the interviewer feel smart.
  - if the the interviewer knows well the topic, then they will be able to ask for more detailed information.
  - if the interviewer does not know the topic, then it will test the ability to explain and break down knowledge as clearly as possible for a novice audience.
- avoid questions expecting know-by-heart answers.
- favor technically good but balanced profiles over technically-strong candidates with weaker soft skills. This is vital to create a team of people that will get along well with each other. This means screening for ["soft skills" and "Emotional intelligence"](https://www.mindtheproduct.com/the-secret-sauce-to-hiring-great-product-people-by-kate-leto/) during interviews.
  - Look for "emotional intelligence": i.e. “the ability to recognise understand and manage our own emotions” and “the ability to recognise understand and influence the emotions of others”.
  - Include behavioral questions. Example: "Tell me about a time when you suggested something that someone disagreed with. What did you say? How did you handle the situation?"
- hide photos and names when selecting resumes to avoid any biases.
- job descriptions usually describe must-haves (usually hard skills) and nice-to-haves (usually soft skills). Instead, it should cover:
  - Purpose – why does this role exist?
  - Accountabilities – what outcomes is it responsible for?
  - Activities – what are the tasks and responsibilities?
  - Behaviours – the key capabilities of EQ
