# Change Log

All notable changes to this project will be documented in this file
automatically by Versionist. DO NOT EDIT THIS FILE MANUALLY!
This project adheres to [Semantic Versioning](http://semver.org/).

# v0.0.28
## (2024-09-27)

* CI: Update checkout settings [Pagan Gazzard]

# v0.0.27
## (2024-03-02)

* workflows: esr: qualify ESR branch matching patterns [Alex Gonzalez]

# v0.0.26
## (2024-03-02)

* esr: use workflows syntax for inputs [Alex Gonzalez]

# v0.0.25
## (2024-03-02)

* esr: qualify ESR base tag to start with base version [Alex Gonzalez]

# v0.0.24
## (2023-10-02)

* Update git author to match bot [Kyle Harding]

# v0.0.23
## (2023-10-02)

* workflows: Switch to balenaOS ESR [bot] for authentication Flowzone App no longer has workflow:write permissions for security reasons. [Kyle Harding]

# v0.0.22
## (2023-09-18)

* build_and_deploy:use authenticate curl to status url [rcooke-warwick]

# v0.0.21
## (2023-08-01)

* Remove excessive permissions from app token [Kyle Harding]

# v0.0.20
## (2023-07-14)

* .github/workflows: Replace GitHub PAT with ephemeral app tokens [Kyle Harding]

# v0.0.19
## (2023-04-21)

* esr: fix pattern for multi-digit revisions [Alex Gonzalez]

# v0.0.18
## (2023-01-14)

* workflows: esr: use semver versioning [Alex Gonzalez]

# v0.0.17
## (2023-01-10)

* esr: remove dispatch event from re-usable workflow [Alex Gonzalez]

# v0.0.16
## (2023-01-10)

* esr: Allow it to be re-usable [Alex Gonzalez]

# v0.0.15
## (2022-11-03)

* esr: Removed schedule [Alex Gonzalez]

# v0.0.14
## (2022-11-03)

* Add ESR workflow [Alex Gonzalez]

# v0.0.13
## (2022-11-03)

* Switch balenaCI to flowzone [Alex Gonzalez]

# v0.0.12
## (2022-10-10)

* workflows: build_and_deploy: use a single prefix for test jobs [Alex Gonzalez]

# v0.0.11
## (2022-10-10)

* build_and_deploy: Add description to deployTo input argument [Alex Gonzalez]
* build_and_deploy: add workerType input argument [Alex Gonzalez]
* build_and_deploy: Identify merge commit after checking out latest tag [Alex Gonzalez]

# v0.0.10
## (2022-08-02)

* build_and_deploy: Ammend debug message [Alex Gonzalez]

# v0.0.9
## (2022-07-15)

* build_and_deploy: Set final flag according to tests status [Alex Gonzalez]

# v0.0.8
## (2022-07-15)

* build_and_deploy: Keep waiting for jobs to complete [Alex Gonzalez]

# v0.0.7
## (2022-07-12)

* Do not wait for Jenkins jobs to complete [Alex Gonzalez]

# v0.0.6
## (2022-07-08)

* build_and_deploy: Adapt for ESR releases [Alex Gonzalez]

# v0.0.5
## (2022-05-27)

* workflows: build_and_deploy: Pull action from balena-os [Alex Gonzalez]

# v0.0.4
## (2022-05-27)

* workflows: build_and_deploy: Parametrize environment and finalize [Alex Gonzalez]

# v0.0.3
## (2022-05-27)

* build_and_deploy: Don't specify the on events, and require secrets input [Alex Gonzalez]

# v0.0.2
## (2022-05-27)

* Add build_and_deploy workflow [Alex Gonzalez]
