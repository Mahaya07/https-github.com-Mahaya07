# CI/CD Integration – Jenkins & GitLab CI (QA Basics) 🔄

This repository documents my **beginner-level understanding of CI/CD pipelines** from a **Quality Assurance perspective**.

The focus is on how QA supports CI/CD processes, not on infrastructure or DevOps setup.

---

## 🔹 What is CI/CD?

- **Continuous Integration (CI)**:  
  Code changes are automatically built and tested after each commit.

- **Continuous Delivery (CD)**:  
  Ensures the application is always in a deployable state after passing tests.

---

## 🔹 CI/CD Flow (QA Perspective)

1. Developer pushes code to repository
2. CI pipeline is triggered automatically
3. Automated tests are executed
4. Test results are generated
5. QA reviews failures and supports release decisions

---

## 🔹 Jenkins – Basic Understanding

- Jenkins is a CI tool used to automate builds and test execution
- Pipelines are created to run tests on code changes
- QA validates test results and pipeline stability

---

## 🔹 GitLab CI – Basic Understanding

- GitLab CI uses YAML-based pipelines
- Pipelines are defined inside `.gitlab-ci.yml`
- Tests are executed automatically during pipeline runs

---

## 🔹 QA Responsibilities in CI/CD

- Ensure test coverage and reliability
- Analyze pipeline failures
- Validate test results before release
- Collaborate with developers on fixes

---

## 🔹 Learning Status

🚧 Beginner level – learning CI/CD concepts step by step with focus on QA involvement.

---

## 🔧 Jenkins Pipeline (Beginner)

This repository includes a basic Jenkins pipeline example to demonstrate
how automated tests can be executed as part of a CI process from a QA perspective.

The pipeline includes stages for:
- Code checkout
- Build
- Test execution
- Result reporting

## 🔧 GitLab CI (Beginner)

This repository includes a basic GitLab CI pipeline defined using `.gitlab-ci.yml`
to demonstrate how automated tests can be executed during CI from a QA perspective.

The pipeline includes:
- Build stage
- Test stage



## 👩‍💻 Author

Mahaya Zeb Khan  
QA Professional | Learning CI/CD for Testing

