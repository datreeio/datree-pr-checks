## Harness the intelligence of datree’s code components catalog in the context of your pull request! :sunglasses:

datree can be integrated with GitHub checks, so for every pull request, the datree BOT will provide a layer of best practices & insights based on your organization’s catalog.

***

### Best Practices Layer:

:black_small_square: Do not include secret file(s)   
:black_small_square: Include mandatory files: .gitignore   
:black_small_square: Keep project dependencies dir out   
:black_small_square: Block unverified user(s)  
:black_small_square: Check code component version  
:black_small_square: Verify changes in related files: manifest & manifest-lock  
:black_small_square: Exclude unwanted files: personal files  

***

### Insights Layer:
#### 1) Repository Related:
:black_small_square: When was the last commit to the default branch  
:black_small_square: When was the last commit by the pull request opener to the default branch  
:black_small_square: What is the code contributing percentage by the pull request opener to the default branch  

#### 2) Code Components Related:
|Categories|Event Details|
|:---|:---|
|:tada: New Code Components	| New code components in the scope of your repository and organization|
|:package: Version Changes	| All the version changes (upgrade / downgrade) made in the pull request |
|:outbox_tray: Removed Code Components | Code components which were removed from your manifest file |
|:chart_with_upwards_trend: Usage Digest | Each file related to a specific code component-related event (added / updated / removed) |

:point_right: &nbsp;&nbsp; We also provide the number of people and repositories in your organization using each code component, and update you whenever there is a **new code component** in your organization’s dev stack! &nbsp;&nbsp; :point_left:

***
### Cut the BS (:poop:), I want to see what it looks like!

You can checkout the open pull requests in this repository - [this one](https://github.com/datreeio/datree-pr-checks/pull/5/checks?check_run_id=9131499) is a good exmaple :octocat:

***

### :book: &nbsp;&nbsp;Glossary
**Code Components** - These are the building blocks used to build applications and have a footprint in your codebase. Code component can be different types of technologies (e.g. docker), open source (e.g npm/express), internal packages or any other “lego bricks” defined by the organization.

// test
another test
another test
