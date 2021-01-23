# Product Management

Best product management know-how

1. [Vision](#vision)
1. [Values](#values)
1. [Strategy](#strategy)
1. [Product Design](#product-design)
1. [Analytical](#analytical)
1. [Product Development](#product-development)
1. [Team management](#team-management)
1. [Recruitment](#recruitment)

## Vision

- Prioritize as much as possible:

  > “People think focus means saying yes to the thing you've got to focus on. But that's not what it means at all. It means saying no to the hundred other good ideas that there are. You have to pick carefully. I'm actually as proud of the things we haven't done as the things I have done. Innovation is saying ‘no’ to 1,000 things.”
  >
  > \- Steve Jobs

- Aim for 10x, not 10%
- Take a long term view
- Make contact with the real world early
- Embrace failure as learning
- Fall in love with the problem, not the solution
- Be creative

  > If at first the idea is not absurd, then there is no hope for it.
  >
  > \- Albert Einstein

## Values

- **Challenge everything & inspire innovation through healthy discord**.

  The ability to speak freely, disagree with others’ opinions, and express one’s point of view each correlates strongly with how innovative the company is. The more people can speak up, the more groundbreaking the company’s progress.

  Foster questions such as "What ifs" and "Why does it have to be this way". Fight against conventional ways of thinking and behaving.

- **The system must protect the individuals**.

  A bug introduced in the latest commit? this is because of a missing test. The tests were not run before merging the feature branch? A continuous integration build should be set up to prevent merging any branch without passing tests. An architecture anti-pattern has been committed? a linting rule should be set up to detect and prevent such pattern. Botching developments last minutes? review how planning is made. Developers staying late and swamped with work? this might be due to poor priorization or resource management. etc

  Think [poka-yoke](https://en.wikipedia.org/wiki/Poka-yoke).

## Strategy

### Situation analysis

- 5 C's
  - Company
  - Customers
  - Competitors
  - Collaborators
  - Climate: Political Economic Social/Cultural Technological Environmental Legal (PESTLE)
- SWOT Analysis
  - Strengths
  - Weaknesses
  - Opportunities
  - Threats
- Porter's Five Forces
  - Competitive Rivalry
  - Supplier Power
  - Buyer Power
  - Threat of Substitution
  - Threat of New Entry

### Competitive analysis

- VRIN score
  - Value: What is the perceived value of the product?
  - Rarity: How innovative/different/unique is the product?
  - Inimitable: How difficult is it to replicate the product?
  - Non-substitutable: Can your customers not live without the product?
- [Economic moat](https://www.cbinsights.com/research/report/business-moats-competitive-advantage)
  - Network Effect moat: marketplace, data, platform
  - Cost moat: cost advantage, sunk cost, switching cost
  - Cultural moat: brand, tradition
  - Resource moat: intellectual property, knowledge, regulatory
- Unique Selling Proposition
  - What your brand does well
  - What consumers want
  - What your competitors do well

## Product Design

- a design session with written specifications must precede any written code
- include users in your design sessions

### Design Frameworks

- [CIRCLES](https://www.impactinterview.com/2016/06/circles-method-product-design-framework/)
  - Comprehend situation: what? Who? Why? How?
  - Identify customer: personas
  - Report customer needs: as XX, I want YY so that ZZ
  - Cut through priorisation
  - List solutions
  - Evaluate trade offs
  - Summarize recommendation
- [BUS](https://uxplanet.org/the-bus-product-design-framework-4e9fb6f81bcf)
- [UDR](https://blog.tryexponent.com/less-linear-approach-circles-product-design/)
- [Organizational Strategy Templates](http://www.drawtoast.com/templates.html)
- Ideation methods: [Re-expression, Revolution, Random links](https://www.interaction-design.org/literature/article/three-ideation-methods-to-enhance-your-innovative-thinking)

### Priorization Frameworks

- Value/Impact vs Complexity/Effort
  - High impact & Low effort: quick wins
  - High impact & High effort: major projects
  - Low impact & Low effort: fill-ins
  - Low impact & High effort: thankless tasks
- Weighted Scoring
- [RICE Scoring Model](https://www.productplan.com/glossary/rice-scoring-model/)
  - Reach
  - Impact
  - Confidence
  - Effort
- Eisenhower Matrix
  - Important & Urgent: Do
  - Important & Not Urgent: Schedule
  - Not Important & Urgent: Delegate
  - Not Important & Nor Urgent: Delete
- MoSCoW
  - Must-have
  - Should-have
  - Could-have
  - Will-not-have

### Resources

- [software UX interview guide template](software-ux-interview-guide.md)
- [persona template](persona-template.md)

## Analytical

- [HEART](https://www.interaction-design.org/literature/article/google-s-heart-framework-for-measuring-ux)
  - Happiness
  - Engagement
  - Adoption
  - Retention
  - Task success
- [GAME](https://hackernoon.com/metrics-game-framework-5e3dce1be8ac)
  - Goals
    - User goals
    - Business goals
  - Actions (AAARR)
    - Acquisition
    - Activation
    - Retention
    - Referral
    - Revenue
  - Metrics
    - Direct vs Proxy
    - Individual vs Aggregate
    - Magnitude vs Ratio
    - Intrinsic vs. Heuristic
  - Evaluations
    - Evaluating Metrics
    - Evaluating Actions
    - Evaluating Goals

## Product Development

- follow a Kanban-like agile methodology as much as possible, to lower the pressure on individuals and the temptation to botch developments. Do not be dogmatic about it.
- be iterative as much as possible: each development should be broken down into tiny pieces that should be quick to implement and review. Use feature flag to help merging features sooner.
- give rythm via scheduled, regular release where all committed developments are in.
- spread key required developments across releases and plan those in advance so that they are ready early in the release cycle.
- make a Release Candidate before the final release with a specific trial period that can't be reduced if tests coverage are not good.
- must have:
  - do Code Reviews.
  - never test the main branch: enforce all tests and linting are passing before merging on the main branch.
  - have end-to-end tests and good unit/integration tests coverage.
  - deprecate anti patterns with linters as soon as they are spotted.
- developments should (from the least to the most complex):
  - meet technical & functional requirements
  - prevent regression via unit, integration and e2e tests
  - design architecture and use patterns that ease support & extendability
  - enforce design in the long term. Ex: separate packages to ensure code isolation

## Team management

- meet with each individual of the team for 60 minutes every month or more with direct/honnest feedback from both sides.
  - Take notes of each interview.
  - Conduct "stay interview" on a regular basis to check in how they are feeling about the job with questions such as:
    - "What motivates you to stay here?"
    - "What might cause you to leave?"
    - "Do you feel that you are challenged?"
    - "What changes would you make to your job if you could?”
  - This is probably the single most powerful tool available to improve people and processes and prioritize what to focus on next.
- favor [the ability to speak up freely over anonymous feedback](https://www.fastcompany.com/40518499/my-company-is-killing-anonymous-employee-feedback-heres-why): "Anonymity reinforces the idea that it’s risky to speak up.". Cf [Values](#values).
- organize post-mortem sessions on a regular basis to collectively share positive feedback and things to improve as well as ways to address those issues.
- foster safe environment where individuals help and trust each other: stealing work to achieve a deadline faster, help on merging a development...
- organize regular activities & outings with the team (bar, team lunch, climbing, bowling, laser tags...) sponsored or not to create a sense of camaraderie.
- job sculpt when possible: adapt task to each individual's strengths and desires.
- favor standard practices, patterns & tools as well as documentation for rapid & cheaper integration in a context of job hopping.
- provide transparency and share/document:
  - Roadmap: each team member's priority dev for next cycle.
  - Team's vacation and remote work.
  - HR common's questions: rules for working remotely, time off, traveling, expense, paperwork, visas...
  - Matrix skills detailing expected expertise and how to progress to the next level.

### Frameworks

- DACI
  - Driver
  - Approver
  - Contributors
  - Informed

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
