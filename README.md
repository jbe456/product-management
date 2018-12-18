# Product Management

Best product management know-how

## Product Development

- as much as possible, follow a Kanban-like agile methodology to lower the pressure on individuals and the temptation to botch devlopments.
- prioritize as much as possible:

  > “People think focus means saying yes to the thing you've got to focus on. But that's not what it means at all. It means saying no to the hundred other good ideas that there are. You have to pick carefully. I'm actually as proud of the things we haven't done as the things I have done. Innovation is saying ‘no’ to 1,000 things.”
  >
  > \- Steve Jobs

- be iterative as much as possible: each developoment should be broken down into tiny pieces that should be quick to implement and review.
- must have:
  - do Code Reviews.
  - never test the main branch: enforce all tests and linting are passing before merging on the main branch.
  - have end-to-end tests and good unit/integration tests coverage.
  - deprecate anti patterns with linters as soon as they are spotted.

## UX

- a design session with written specifications must precede any written code
- include users in your design sessions

## Values

- **the ability to speak freely, disagree with others’ opinions, and express one’s point of view** each correlates strongly with how innovative the company is. The more people can speak up, the more groundbreaking the company’s progress.
- **the system must protect the individuals**.

  A bug introduced in the latest commit? this is because of a missing test. The tests were not run before merging the feature branch? A continuous integration build should be set up to prevent merging any branch without passing tests. An architecture anti-pattern has been committed? a linting rule should be set up to detect and prevent such pattern. Botching developments last minutes? review how planning. Developers staying late and swamped with work? this might be due to poor priorization or resource management. etc

  Think [poka-yoke](https://en.wikipedia.org/wiki/Poka-yoke).

## Team management

- meet with each individual of the team for 60 minutes every month with direct/honnest feedback from both sides. Take notes of each interview. This is probably the single most powerful tool available to improve people and processes and prioritize what to focus on next.
- favor [the ability to speak up freely over anonymous feedback](https://www.fastcompany.com/40518499/my-company-is-killing-anonymous-employee-feedback-heres-why): "Anonymity reinforces the idea that it’s risky to speak up.". Cf [Values](#values).
- organize post-mortem sessions on a regular basis to collectively share positive feedback and things to improve as well as ways to address those issues.
- organize regular activities & outings with the team (bar, team lunch, climbing, bowling, laser tags...) sponsored or not to create a sense of camaraderie.

## Recruitment

- favor interview conditions that are as close as possible to real-life tasks: i.e. similar to what the candidates used or will use to develop. [Avoid whiteboards...](https://medium.com/javascript-scene/tech-hiring-has-always-been-broken-heres-how-i-survived-it-for-decades-b7ac33088de6)
- test candidates how well they know what they pretend to know rather than how well they know what the interviewer knows. This implies also testing the ability to explain and break down knowledge as clearly as possible for a novice audience.
- Avoid questions expecting know-by-heart answers
- favor technically good but balanced profiles over technically-strong candidates with weaker social skills. This is vital to create a team of people that will get along well with each other.
- hide photos and names when selecting resumes to avoid any biases.
