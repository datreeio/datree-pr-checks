## The power of datree catalog in context of your pull request! :sunglasses:

datree is now integrated with GitHub checks, so for every pull request, we will provide a layer of best practice & insights based on your organization catalog.

***
### Best Practice Verification:
#### 1) Unused Code Components in Manifest
#### 2) Unverified Users

***

### Insights Layer:
#### 1) Repository Related:
:black_small_square: When was the last commit to the default branch  
:black_small_square: When was the last commit by the pull request opener to the default branch  
:black_small_square: Code contributing percentage by the the pull request opener to the default branch  

#### 2) Code Components Related:
|Categories|Event Details|
|:---|:---|
|:tada: New Code Components	| New code components in the scope of your repository and organization|
|:package: Version Changes	| All the version changes (upgrade / downgrade) made in the pull request |
|:outbox_tray: Removed Code Components | Code components which removed from your manifest file |
|:chart_with_upwards_trend: Usage Digest | In each files there was a code component related event (add / updated / removed) |

:point_right: &nbsp;&nbsp; We will also provide info about **how many people and repositories** are using each code component in your organization, or if it a **new code component** in your organization dev stack! &nbsp;&nbsp; :point_left:

***
### Cut the BS (:poop:), I want to see what it looks like!

You can checkout the open pull requests in this repository - [this one](https://github.com/datreeio/datree-pr-checks/pull/5) is a good exmaple :octocat:

***
### What is Next on our Roadmap?
:black_square_button: More built-in best practice verification   
:black_square_button: Custom policy rules verification   
:black_square_button: PR repositories managment  

:clock2: Stay tuned for the **next release** at August 28th

***

#### :book: &nbsp;&nbsp;Glossary
**Unused Code Component in Manifest** - this is when open sources or internal packages are listed in the manifest file but are not imported into any of the files in the repository. Removing extraneous code components will save build time, and long-term maintenance overhead, but will have no effect on your code.

**Unverified Users** - this happens when the git author info is different than the git committer details. If you authored the code and made the commit, you should adjust your settings to match your GitHub account in order to connect the commit to the correct GitHub user.

**Code Components** - Code components are the building blocks used to build applications and have a footprint in your codebase. Code component can be different types of technologies (e.g docker), open source (e.g npm/express), internal packages or any other defined “lego bricks” defined by the organization
