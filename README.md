<h1 align="center">Al Imran</h1>

<p align="center">
  <strong>QA Lead</strong> · Essen, Germany · Remote at <a href="https://a-d.com.au">AD Group</a>, Australia
</p>

<p align="center">
  <img src="https://img.shields.io/badge/tests-passing-brightgreen?style=flat-square" alt="tests passing" />
  <img src="https://img.shields.io/badge/coverage-shifting%20left-blue?style=flat-square" alt="coverage" />
  <img src="https://img.shields.io/badge/flakiness-0%25-success?style=flat-square" alt="flakiness" />
  <img src="https://img.shields.io/badge/based%20in-Essen,%20DE-informational?style=flat-square" alt="location" />
</p>

---

```bash
$ npx playwright test profile.spec.ts

Running 6 tests using 1 worker

  ✓  builds QA functions from zero                              (3y)
     › first QA hire at AD Group; designed the process, then hired into it
  ✓  leads a team of 3, scaling to 5                             (1y)
     › Showcase · AD Revamp · Development ID
  ✓  writes API automation that survives contact with reality   (520ms)
     › Playwright + TypeScript · fixtures over boilerplate · contract-first
  ✓  ships performance baselines, not vibes                      (2.4s)
     › Grafana k6 · thresholds in CI, not in a spreadsheet
  ✓  builds QA tooling with AI instead of talking about it      (14★)
     › autonomous QA agent in VS Code · Claude + Jira for requirements analysis
  ✓  answers the question nobody asked yet                       (180ms)
     › Stack Overflow · Appium community · ezyAutomation blog

  6 passed (3y 2m)
```

---

## `describe('what I actually do')`

**Test strategy before test code.** Requirements and design review first, scope agreed per epic, regression and E2E gates before production. Writing tests is the cheap part; deciding what deserves one is the job.

**Automation that doesn't rot.** Fixture architecture, one spec per endpoint, deterministic data. A suite nobody trusts is worse than no suite — so flake gets fixed, not retried.

**Documentation is the contract.** If an API behaves differently from what it documents, that's a test worth writing. And worth leaving red until someone fixes it.

**AI where it earns its place.** Requirements analysis, test case generation, change-impact analysis. Not as a novelty — as the thing that gives three engineers the reach of six.

---

## `describe('repositories')`

| Project | Stack | What it is |
|---|---|---|
| **[ai-qa-assistant](https://github.com/imransdet/ai-qa-assistant)** ⭐14 | TypeScript | Autonomous QA agent in VS Code. Point it at a staging URL with requirements in any form — Jira ticket, PRD, acceptance criteria, design link — and it takes it from there |
| **[payment-api-test](https://github.com/imransdet/payment-api-test)** | TypeScript | Playwright API suite for an async payment flow. Contract-first against an OpenAPI spec, with measured polling instead of fixed waits — and two tests left deliberately red to document real contract violations |
| **[playwright-e2e-test-realworld-app](https://github.com/imransdet/playwright-e2e-test-realworld-app)** | TypeScript | E2E suite covering UI and API, wired into a full CI/CD workflow |
| **[performance-test-with-grafana-k6](https://github.com/imransdet/performance-test-with-grafana-k6)** | JavaScript | k6 performance testing framework |
| **[api-test-automation-postman-newman](https://github.com/imransdet/api-test-automation-postman-newman)** | JavaScript | Postman collections, CI-integrated via Newman |
| **[cypress-test-web-api](https://github.com/imransdet/cypress-test-web-api)** | TypeScript | UI and API coverage with Cypress, Page Object Model |
| **[appium-java-for-mobile-app](https://github.com/imransdet/appium-java-for-mobile-app)** | Java | Appium framework for native, hybrid and web Android. Clone and start writing |

---

## `describe('toolchain')`

```yaml
automation:    [ Playwright, Cypress, Selenium, Appium ]
api:           [ Postman, Newman, REST, OpenAPI ]
performance:   [ Grafana k6 ]
ci_cd:         [ GitHub Actions, Jenkins, Docker ]
languages:     [ TypeScript, JavaScript, Java ]
management:    [ Jira, Qase ]
ai:            [ Claude, MCP ]
```

<p>
  <img src="https://playwright.dev/img/playwright-logo.svg" alt="playwright" width="36" height="36"/>
  <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/6e46ec1fc23b60c8fd0d2f2ff46db82e16dbd75f/icons/cypress.svg" alt="cypress" width="36" height="36"/>
  <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="36" height="36"/>
  <img src="https://cdn.simpleicons.org/appium/662D91" alt="appium" width="36" height="36"/>
  <img src="https://cdn.simpleicons.org/k6/7D64FF" alt="k6" width="36" height="36"/>
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="36" height="36"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="36" height="36"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="36" height="36"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="36" height="36"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="nodejs" width="36" height="36"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" alt="github actions" width="36" height="36"/>
  <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="36" height="36"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="36" height="36"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jira/jira-original.svg" alt="jira" width="36" height="36"/>
</p>

---

## `describe('find me elsewhere')`

<p>
  <a href="https://www.linkedin.com/in/al-imran-56675092/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" /></a>
  <a href="mailto:imranreee@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
  <a href="https://stackoverflow.com/users/6333173/al-imran"><img src="https://img.shields.io/badge/Stack%20Overflow-F58025?style=for-the-badge&logo=stackoverflow&logoColor=white" alt="stack overflow" /></a>
  <a href="https://www.hackerrank.com/imranreee"><img src="https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black" alt="hackerrank" /></a>
  <a href="https://discuss.appium.io/u/Al_Imran/activity"><img src="https://img.shields.io/badge/Appium%20Community-662D91?style=for-the-badge&logo=appium&logoColor=white" alt="appium community" /></a>
  <a href="https://ezyautomation.blogspot.com/"><img src="https://img.shields.io/badge/ezyAutomation-FF5722?style=for-the-badge&logo=blogger&logoColor=white" alt="blog" /></a>
</p>

---

<details>
<summary><code>afterAll()</code> — three things I'd argue about over coffee</summary>

<br>

**Deterministic test data over random.** Random data finds a bug once and then you can't reproduce it. The inputs that actually break things — single characters, Unicode, boundary values — are ones you choose on purpose.

**Poll, don't sleep.** A fixed `wait(3000)` is a bet that the system will never be slower than it was on your laptop. Measure the real distribution, set a ceiling with headroom, and assert that a terminal state is reached — not how long it took.

**A red test is a finding, not a failure.** The instinct to loosen an assertion until it passes is the one habit that quietly destroys a suite's value.

</details>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=imransdet&layout=compact&hide_border=true&theme=transparent" alt="top languages" />
</p>
