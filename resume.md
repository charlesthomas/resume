# Charles Thomas
[ch@rlesthom.as](mailto:ch@rlesthom.as) / [charlesthomas.github.io](https://charlesthomas.github.io)

### B.S. Computer Network and System Administration
**Michigan Technological University - Graduated 2008**

### Release Engineer IV - Mezmo (LogDNA) - Oct 2020 to Present

**Responsibilities**

- Develop and Distribute Deployment Pipeline Tooling
- Create and Educate on Deployment Pipeline Best Practices
- Support CI/CD for Microservices Application Stack
  - 350+ repos across 2 GitHub orgs
  - ~20 environments; ~15 of which are production
- Maintain CI/CD Systems
  - Jenkins
  - [Razee](https://github.com/razee-io)

**Achievements**

- Reduced Maximum Time to Deploy by 75%
  - From 20 min to 5 min
- Created custom tooling for syncing updates to repo templates
  - When the templates change, PRs are opened to the repos that use them, bringing them up to date with the template
- Created custom tooling to inject metadata into k8s manifests to aid in troubleshooting in live environments
  - Custom tool is 80% faster than previous off-the-shelf tool

### Information Systems Engineer - Datastax - Aug 2020 to Oct 2020 
(Started working on the team mid-Feb; official title change 8/1)

**Responsibilities**

- Create, maintain, and monitor company Jenkins infrastructure
    - 15+ Jenkins servers
- Own product delivery pipeline from package builds to hosting

**Accomplishments**

- Converted all existing open-source Jenkins servers to CloudBees Core Client Masters
    - Unified authentication and authorization
    - Shared resources between Jenkins servers
- Redesigned and reimplemented product delivery pipeline
    - Previous implementation was locked to a single Jenkins server & NFS share
    - New pipeline uses Swift object storage to move artifacts between any Jenkins server
    - All release pipeline resources including the Jenkins jobs themselves live in a single repo
        - Using Jenkins Job DSL plugin

### Software Engineer in Test - Datastax - Jun 2014 to Aug 2020
**Responsibilities**

- Build and maintain test framework in Java
    - UI testing via Selenium
    - API testing via GraphQL
- Maintain Python test framework for legacy product
- Build and maintain Jenkins jobs via Pipeline

**Accomplishments**

- Drove conversion of Jenkins jobs to Jenkins Pipeline
- Integrated xunit_tools reporting into Jenkins
- Moved Jenkins test infrastructure to use dynamic executors running in OpenStack
- Built Selenium testing framework in Python
- Merged stand-alone Selenium test framework into existing functional testing automation framework
- Helped other product testing team build Selenium test framework in Python
	- Helped same product testing team convert Python Selenium framework to Java
- Contributed [minor patch](https://github.com/SeleniumHQ/selenium/pull/244) to Selenium project to quiet output when testing locally in Safari

### Senior Software Engineer, QA - Shopwiki.com - Aug 2012 to Jun 2014
**Responsibilities**

- QA team lead
	- Assign cases & projects to QA Team members
	- Train new QA team members
- Write Python tests for new UI features on [shopwiki.com](http://shopwiki.com), compare.com, and rebatecove.com
- Maintain existing UI test suite for same
- Work closely with development team to resolve bugs

**Accomplishments**

- Built system for collecting performance data using open source tools
- Reduced false-negative tests in UI testing suite by over 75%
- Reduced testing time per release from multiple days to a few hours
- Completed QA testing cycle for over 60 major and minor UI releases
- Built the entire Selenium test framework for compare.com

### Application Operations Engineer - CheetahMail - Aug 2010 to Aug 2012
**Responsibilities**

- Develop custom internal tools for increasing team efficiency
- Troubleshoot / investigate & report application defects
- Monitor system performance; investigate abnormalities
- Create / update / maintain internal support documentation
- Train / assist team members
- Assist in major software releases

**Accomplishments**

- Created 4 Perl tools to increase team efficiency
	- Saved approximately 3 hours per ticket with one tool
	- Enabled pulling of previously unobtainable data with another
- Won 2011 Q1 Experian CheetahMail Pinnacle Award for individual performance
- Trained entire remote-office support team during their on-boarding
- Created or updated approximately 35 individual internal support wikis
	- Top 20 historical contributor

### Senior Support Analyst - TimeLink International - Jun 2008 to Aug 2010
**Responsibilities**

- Test and deploy software upgrades
	- Create additional database scripts for custom functions
- Migrate customer databases for local testing
- Work with development team to identify bugs
- Test and repair custom Linux embedded devices
- Train new support team members on all items listed above
	- Create training documentation
- Act as escalation point for less experienced members of the support team
- Lead teams for special internal projects
- Draft system maintenance emails for hosted customers

**Accomplishments**

- Acted as support team lead for approximately 25% of TimeLink6 customers
- Created 6 Perl based data parsing tools deployed in customer production environments
	- One script saved 2 weeks of development time – meeting otherwise unattainable customer deadline
	- Created another script in 2 days to meet customer deadline – including requirement gathering, development, customer testing, and deployment
- Created two inventory systems with PHP/MySQL
	- Prior to first inventory system, company had no way of tracking devices
	- Second inventory system added data auditing and user configuration
