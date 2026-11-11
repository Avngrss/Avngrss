# Yury Siadou

## Quality Assurance Engineer | Manual Testing | Playwright Automation | AI-Driven QA

I am a Quality Assurance Engineer working across manual testing, test automation, API testing, and quality engineering.

I build web test automation with Playwright and TypeScript, design test documentation and testing strategies, investigate product risks, and integrate automated checks into CI/CD pipelines.

I also use AI in daily QA work for requirements analysis, test documentation, test planning, technical research, prompt design, and the development of specialized agents and reusable QA workflows. My main interest is controlled AI-assisted testing, where agents can support engineering work without silently changing requirements, weakening validations, or hiding unsupported conclusions.

## Manual Testing

- Functional, regression, integration, exploratory, and usability testing
- Requirements, user stories, and acceptance criteria analysis
- Test strategy and test plan preparation
- Risk-based testing and test scope prioritization
- Test scenario, checklist, and test case design
- Positive, negative, boundary-value, and state-transition testing
- End-to-end business flow validation
- Release and regression scope definition
- Test execution analysis and quality reporting
- Reproducible bug reports with clear steps, expected results, actual results, and supporting evidence
- Defect investigation using browser console, network traffic, storage, logs, screenshots, and session evidence
- Root-cause isolation across product behavior, test data, integrations, environments, and automation
- REST API testing, including requests, responses, headers, status codes, payloads, schemas, and error handling
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
- Deterministic and reusable test data
- Parameterized and data-driven test scenarios
- Cross-browser testing with Chromium, Firefox, and WebKit
- Network interception, response validation, and controlled mocking
- Storage state and authenticated session management
- Playwright projects, tags, annotations, retries, and execution configuration
- Failure analysis using traces, screenshots, videos, logs, and reports
- Flaky test investigation and separation of product, environment, data, and automation failures
- Test quality checks with ESLint and project-specific rules
- Automated execution and quality gates in GitHub Actions
- Test result and artifact publication in CI/CD
- Reporting and execution analysis with Allure
- Maintainability reviews for generated and manually written tests

## AI-Assisted Testing

I design QA workflows in which AI supports analysis and implementation while requirements, evidence, and engineering decisions remain explicit and reviewable.

My work in this area includes:

- AI-assisted requirements and acceptance criteria analysis
- Test plan, test case, checklist, and technical documentation generation
- Agent-based test planning, generation, execution, analysis, and maintenance
- Plan-first workflows that separate approved test obligations from implementation
- Specialized QA agents with explicit roles, inputs, outputs, and authority boundaries
- Reusable skills, prompts, rules, templates, and project instructions
- Context preparation for AI agents using project facts and approved sources
- Validation of AI-generated and AI-modified tests
- Automated quality gates for test structure, architecture, and implementation
- Traceability between requirements, test plans, automated tests, executions, and defects
- Evidence-based analysis of test failures and product risks
- Controlled healing that restores test implementation without weakening the original validation
- Stop conditions when available evidence is insufficient for a safe change
- Human approval for decisions that affect requirements, scope, expected behavior, or strength of evidence

The goal is not to make tests green at any cost. The goal is to use AI to make QA work faster and more systematic while preserving product obligations, test reliability, and human control.

## Current Work

### Beyond Playwright Agents

I am writing **Beyond Playwright Agents**, a technical book about designing controlled AI-assisted testing systems around Playwright agents.

The book examines what is required beyond basic test generation. Planner, Generator, and Healer can provide a strong execution layer, but they still need approved inputs, project context, authority boundaries, evidence requirements, quality gates, and explicit Stop behavior.

The book connects these elements into a complete engineering workflow:

- turning requirements into reviewable test obligations;
- treating the test plan as a contract for implementation;
- defining responsibilities and boundaries for each agent;
- separating observed product behavior from approved requirements;
- validating generated tests without weakening their assertions;
- maintaining traceability between obligations, tests, results, and defects;
- allowing healing only when a safe correction can be supported by evidence;
- keeping human decisions at the points where requirements, scope, evidence, or expected behavior may change.

The central principle is that a passing test is valuable only when it correctly verifies an approved product obligation.

### Playwright AI Workflow Kit

I am developing a reusable **Playwright AI Workflow Kit** that implements the architectural principles explored in the book.

The kit supports a controlled workflow for:

1. analyzing feature inputs and approved sources;
2. identifying test obligations and coverage risks;
3. preparing a structured and reviewable test plan;
4. generating Playwright tests from the approved plan;
5. validating test architecture and implementation quality;
6. executing tests and collecting evidence;
7. analyzing failures and distinguishing their likely source;
8. proposing safe maintenance changes;
9. stopping when available evidence does not justify a change.

The kit combines Playwright agents, reusable skills, project instructions, architecture rules, quality gates, CI/CD checks, execution evidence, and traceability. It is a practical implementation of controlled AI-assisted automation rather than an autonomous replacement for engineering judgment.

## Planned Work

### AI-Assisted k6 Framework

I plan to build a product-agnostic AI-assisted performance testing framework with k6.

The framework will cover reusable workload profiles, authenticated multi-step scenarios, request correlation, deterministic test data, thresholds, run comparison, degradation analysis, capacity findings, CI/CD integration, and evidence-based result analysis.

AI will support scenario preparation and interpretation, while workload assumptions, raw metrics, thresholds, and conclusions remain visible and verifiable.

## Technologies

![Playwright](https://img.shields.io/badge/Playwright-45BA4B?style=flat-square&logo=playwright&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)
https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)
https://img.shields.io/badge/Allure-FF6A00?style=flat-square&logo=qameta&logoColor=white
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black
![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Chrome DevTools](https://img.shields.io/badge/Chrome_DevTools-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
https://img.shields.io/badge/Charles_Proxy-3B82F6?style=flat-square&logo=charles&logoColor=white
https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white

## Contact

https://img.shields.io/badge/LinkedIn-Yury_Siadou-0077B5?style=for-the-badge&logo=linkedin&logoColor=white](https://linkedin.com/in/yury-siadou)
