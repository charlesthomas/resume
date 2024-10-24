# Charles Thomas
- email: [ch@rlesthom.as](mailto:ch@rlesthom.as)
- website: [charlesthomas.dev](https://charlesthomas.dev)
- resume: [PDF download](http://github.com/charlesthomas/resume/releases/latest/download/Charles-Thomas-Resume.pdf)

## Education

### B.S. Computer Network and System Administration
**Michigan Technological University - Graduated 2008**

## Open Source

* [templatron](https://github.com/charlesthomas/templatron)
  * a tool for automatically open PRs to destination repos when the template they were generated from changes
* [homelab](https://github.com/charlesthomas/homelab)
  * a series of micro-services repositories for running a k3s homelab
* [homelab-template](https://github.com/charlesthomas/homelab-template)
  * a repo template that uses `templatron` to automatically update `homelab-*` repos on changes
* [github-action-svu](https://github.com/charlesthomas/github-action-svu)
  * a GitHub Action for using [`svu`](https://github.com/caarlos0/svu) to generate new semantic versions based on commit history
* [bitwarden-cli](https://github.com/charlesthomas/bitwarden-cli)
  * a Docker image for BitWarden's cli
  * created when I discovered that the image formerly listed in [external-secrets documentation](https://github.com/external-secrets/external-secrets/pull/2971) was no longer available

## Skills

| Go      | Kubernetes | Docker  | Python  | Git      | Jenkins  | Linux    |
| ------- | ---------- | ------- | ------- | -------- | -------- | -------- |
| 2 years | 3 years    | 3 years | 9 years | 11 years | 11 years | 20 years |

## Areas of Interest

| Developer Enablement | Automation | Efficiency | Standardization |
| -------------------- | ---------- | ---------- | --------------- |
| Platform Engineering | DevOps     | Security   | Open Source     |

## Experience

### Senior Platform Engineer - InfluxData - Jan 2024 to Present

**Responsibilities**

- Maintain and improve InfluxDB Cloud2 deployment pipeline & tooling
- Operate InfluxDB Cloud2 infrastructure
  - 17 Kubernetes clusters across 3 cloud providers
- Serve as final application support escalation tier for customers
- Participate in on-call rotation

**Achievements**

- Reverse-engineered image auto-promoter tool for readability, maintainability, and performance
  - Previous tool was maintained by a team of 8
  - The new version is a minimum of 15x faster
    - Based on slowest observed run of new tool vs. fastest observed run of old tool
- Added feature via [upstream pull request](https://github.com/kubecfg/kubecfg/pull/415) to a tool used for generating Kubernetes manifests
  - This allowed us to upgrade a 3rd party service without completely rewriting the `jsonnet` library used to render its manifests

### Senior Platform Engineer, Release - Mezmo - Oct 2020 to Nov 2023

**Responsibilities**

- Develop and Distribute Deployment Pipeline Tooling
- Create and Educate on Deployment Pipeline Best Practices
- Support CI/CD for Microservices Application Stack
  - 350+ repos across 2 GitHub orgs
  - ~20 environments; ~15 of which are production
- Maintain CI/CD Systems

**Achievements**

- Reduced Maximum Time to Deploy by 75%
- Designed and developed production-readiness testing framework
  - Capable of running 800 production-readiness tests in 40 seconds
- Designed and developed tool for syncing template changes to repositories using the template

### Information Systems Engineer - Datastax - Feb 2020 to Oct 2020 

**Responsibilities**

- Create, maintain, and monitor company Jenkins infrastructure
    - 15+ Jenkins servers
- Own product delivery pipeline from package builds to hosting

**Accomplishments**

- Converted all existing open-source Jenkins servers to CloudBees Core Client Masters
- Redesigned and reimplemented product delivery pipeline

### Software Engineer in Test - Datastax - Jun 2014 to Feb 2020
**Responsibilities**

- Build and maintain test framework in Java
- Maintain Python test framework for legacy product
- Build and maintain Jenkins jobs via Pipeline

**Accomplishments**

- Moved Jenkins test infrastructure to use dynamic executors running in OpenStack
- Built Selenium testing framework in Python
- Contributed [minor patch](https://github.com/SeleniumHQ/selenium/pull/244) to Selenium project to quiet output when testing locally in Safari

### Senior Software Engineer, QA - Shopwiki.com - Aug 2012 to Jun 2014
**Responsibilities**

- Write Python tests for new UI features on shopwiki.com, compare.com, and rebatecove.com
- Maintain existing UI test suite for same
- Work closely with development team to resolve bugs

**Accomplishments**

- Built system for collecting performance data using open source tools
- Reduced false-negative tests in UI testing suite by over 75%
- Reduced testing time per release from multiple days to a few hours

### Application Operations Engineer - CheetahMail - Aug 2010 to Aug 2012
**Responsibilities**

- Develop custom internal tools for increasing team efficiency
- Monitor system performance; investigate abnormalities
- Create / update / maintain internal support documentation

**Accomplishments**

- Created 4 Perl tools to increase team efficiency
	- Saved approximately 3 hours per ticket with one tool
	- Enabled pulling of previously unobtainable data with another
- Won 2011 Q1 Experian CheetahMail Pinnacle Award for individual performance
- Trained entire remote-office support team during their on-boarding

### Senior Support Analyst - TimeLink International - Jun 2008 to Aug 2010
**Responsibilities**

- Test and deploy software upgrades
- Work with development team to identify bugs
- Test and repair custom Linux embedded devices
- Lead teams for special internal projects

**Accomplishments**

- Acted as support team lead for approximately 25% of TimeLink6 customers
- Created Perl based data parsing tools deployed in customer production environments
- Created inventory systems with PHP/MySQL

---

[The PDF version of this resume is generated automatically.](https://charlesthomas.dev/blog/generating-my-resume-as-a-pdf-with-github-actions-2023-10-14/)
