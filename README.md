## Harness the intelligence of datree’s code components catalog in the context of your pull request! :sunglasses:

datree can be integrated with GitHub checks, so for every pull request, the datree BOT will provide a layer of best practices & insights based on your organization’s catalog.

***
### Best Practice Verification:
#### 1) Unused Code Components in the Manifest
#### 2) Unverified Users

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

You can checkout the open pull requests in this repository - [this one](https://github.com/datreeio/datree-pr-checks/pull/5) is a good exmaple :octocat:

***
### Next on datree’s Roadmap
:black_square_button: More built-in best practice verification   
:black_square_button: Custom policy rules verification   
:black_square_button: PR repositories managment  

:clock2: Stay tuned for the **next release** at August 28th

***

### :book: &nbsp;&nbsp;Glossary
**Unused Code Component in the Manifest** - This is when open sources or internal packages are listed in the manifest file but are not imported into any of the files in the repository. Removing extraneous code components will save build time, and long-term maintenance overhead, but will have no effect on your code.

**Unverified Users** - This happens when the git author info is different than the git committer details. If you authored the code and made the commit, you should adjust your settings to match your GitHub account in order to connect the commit to the correct GitHub user.

**Code Components** - These are the building blocks used to build applications and have a footprint in your codebase. Code component can be different types of technologies (e.g. docker), open source (e.g npm/express), internal packages or any other “lego bricks” defined by the organization.
