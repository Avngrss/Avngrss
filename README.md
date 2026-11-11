# Yury Siadou

## Quality Assurance Engineer | Manual & API Testing | Playwright Automation | AI-Assisted QA

I am a Quality Assurance Engineer working across manual testing, API testing, test automation, and quality engineering.

I build web test automation with Playwright and TypeScript, design test strategies and documentation, investigate product risks, and integrate automated checks into CI/CD pipelines. I also design controlled AI-assisted QA workflows that improve engineering efficiency without allowing agents to silently change requirements, weaken validations, or produce unsupported conclusions.

## Testing and Quality Engineering

- Functional, regression, integration, exploratory, and usability testing
- Requirements, user stories, and acceptance criteria analysis
- Test strategy, test planning, risk-based prioritization, and release scope definition
- Test scenario, checklist, and test case design
- Positive, negative, boundary-value, and state-transition testing
- End-to-end business flow validation
- Test execution analysis and quality reporting
- Reproducible bug reports with clear steps, expected results, actual results, and supporting evidence
- Defect investigation and root-cause isolation using browser console, network traffic, storage, logs, screenshots, and session evidence
- REST API testing covering requests, responses, headers, status codes, payloads, schemas, and error handling
- Authentication, authorization, and integration testing
- OpenAPI and Swagger contract analysis
- API collections and API clients for exploratory and repeatable checks
- Collaboration with developers, product stakeholders, and QA engineers throughout the delivery process

## Test Automation

- End-to-end automation with Playwright and TypeScript
- UI, API, authentication, and multi-step workflow automation
- Test architecture, configuration, fixtures, helpers, and reusable utilities
- Page Object Model and component-oriented abstractions where they improve maintainability
- Stable locators based on user-visible and accessible application behavior
- Synchronization through observable conditions instead of fixed timeouts
- API-based setup, state preparation, verification, and cleanup
- Deterministic, reusable, parameterized, and data-driven test data
- Cross-browser testing with Chromium, Firefox, and WebKit
- Network interception, response validation, and controlled mocking
- Storage state and authenticated session management
- Playwright projects, tags, annotations, retries, and execution configuration
- Failure and flaky test analysis using traces, screenshots, videos, logs, and reports
- Separation of product, environment, test data, and automation failures
- Test quality checks with ESLint and project-specific rules
- CI/CD execution, quality gates, result publication, and artifacts in GitHub Actions
- Reporting and execution analysis with Allure
- Maintainability reviews for generated and manually written tests

## AI-Assisted Testing

I design QA workflows in which AI supports analysis, implementation, execution, and maintenance while requirements, evidence, authority boundaries, and engineering decisions remain explicit and reviewable.

My work in this area includes:

- AI-assisted requirements and acceptance criteria analysis
- Test plan, test case, checklist, and technical documentation generation
- Agent-based test planning, generation, execution, analysis, and maintenance
- Plan-first workflows that separate approved test obligations from implementation
- Specialized QA agents with explicit roles, inputs, outputs, and authority boundaries
- Reusable skills, prompts, rules, templates, and project instructions
- Context preparation using project facts and approved sources
- Validation of AI-generated and AI-modified tests
- Automated quality gates for test structure, architecture, and implementation
- Traceability between requirements, test plans, automated tests, executions, and defects
- Evidence-based analysis of test failures and product risks
- Controlled healing that repairs test implementation without weakening the original validation
- Stop conditions when available evidence is insufficient for a safe change
- Human approval for decisions that affect requirements, scope, expected behavior, or strength of evidence

The goal is not to make tests green at any cost. The goal is to make QA work faster and more systematic while preserving product obligations, test reliability, and human control.

## Current Work

### Beyond Playwright Agents

I am writing **Beyond Playwright Agents**, a technical book about the architecture of controlled AI-assisted testing systems built around Playwright agents.

Planner, Generator, and Healer provide a strong execution layer, but reliable engineering work also requires:

- approved inputs and explicit test obligations;
- a reviewable test plan that acts as an implementation contract;
- clear responsibilities and authority boundaries;
- separation between observed behavior and approved requirements;
- evidence requirements and automated quality gates;
- traceability between obligations, tests, executions, and defects;
- controlled healing that cannot weaken the original validation;
- explicit Stop behavior when evidence is insufficient;
- human decisions where requirements, scope, evidence, or expected behavior may change.

The central principle is that a passing test is valuable only when it correctly verifies an approved product obligation.

### Playwright AI Workflow Kit

[Playwright AI Workflow Kit](https://github.com/Avngrss/playwright-ai-workflow-kit) is a Playwright and TypeScript starter for building controlled AI-assisted test automation workflows in Cursor.

The kit provides rules, skills, slash commands, project context, architecture conventions, and automated quality gates around a plan-first workflow:

1. register the application and its project-specific context;
2. prepare and approve a structured feature test plan;
3. implement ready cases across the required API, UI, or E2E layers;
4. execute targeted tests and collect failure evidence;
5. validate the implementation through quality gates and focused review;
6. diagnose failures and apply only evidence-supported corrections;
7. report coverage and stop when a safe change cannot be justified.

It also includes structured test data and cleanup, authenticated state management, readable failure verdicts, traceability to test cases, Allure 3 reporting, and CI configurations for GitHub Actions and GitLab CI.

The kit is a practical reference implementation of controlled AI-assisted automation, not an autonomous replacement for engineering judgment.

## Planned Work

### AI-Assisted k6 Framework

I plan to build a product-agnostic AI-assisted performance testing framework with k6.

The framework will cover reusable workload profiles, authenticated multi-step scenarios, request correlation, deterministic test data, custom metrics, thresholds, run comparison, degradation analysis, capacity findings, and CI/CD integration.

AI will assist with scenario preparation and result analysis, while workload assumptions, raw metrics, thresholds, evidence, and conclusions remain visible and verifiable.

## Technologies

### Automation and Development

![Playwright](https://img.shields.io/badge/Playwright-45BA4B?style=flat-square&logo=playwright&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)

### API and Performance Testing

![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)

### CI/CD and Reporting

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Allure](https://img.shields.io/badge/Allure-FF6A00?style=flat-square&logo=qameta&logoColor=white)

### Investigation and Development Tools

![Chrome DevTools](https://img.shields.io/badge/Chrome_DevTools-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Charles Proxy](https://img.shields.io/badge/Charles_Proxy-3B82F6?style=flat-square&logo=charles&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

## Contact

https://img.shields.io/badge/LinkedIn-Yury_Siadou-0077B5?style=for-the-badge&logo=linkedin&logoColor=white](https://linkedin.com/in/yury-siadou)
