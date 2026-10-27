# My GNR653 notes
Introduction to Git (Version Control):
Definition: Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.
Source: https://git-scm.com/book/ms/v2/Getting-Started-About-Version-Control

There are two types of Version Control Systems:
    1. Centralized Version Control System
    2. Distributed Version Control System

Centralized Version Control System: In a centralized version control system (CVCS), also known as a centralized source control or revision control system, a server acts as the main centralized repository which stores every version of code. Using centralized source control, every user commits directly to the main branch, so this type of version control often works well for small teams, because team members have the ability to communicate quickly so that no two developers want to work on the same piece of code simultaneously. Source: https://about.gitlab.com/topics/version-control/what-is-centralized-version-control-system/

Distributed Version Control System: In software development, distributed version control (also known as distributed revision control) is a form of version control in which the complete codebase, including its full history, is mirrored on every developer's computer. Source: https://en.wikipedia.org/wiki/Distributed_version_control

Git: Git is a distributed version control system that enables software development teams to have multiple local copies of the project's codebase independent of each other. These copies, or branches, can be created, merged, and deleted quickly, empowering teams to experiment, with little compute cost, before merging into the main branch (sometimes referred to as the master branch). Git is known for its speed, workflow compatibility, and open source foundation. Source: https://about.gitlab.com/topics/version-control/what-is-git-version-control/


Git Branches:
Branches keep your team’s development work organized and separated. When multiple people work on different features simultaneously, branches prevent changes from conflicting with each other. Each branch acts as an isolated workspace where you implement new features, fix bugs, or experiment with ideas.

With branches, your team can:
    * Work on separate features without disrupting the main codebase.
    * Review proposed changes before they affect the rest of the project.
    * Roll back problematic changes without affecting other work.
    * Deploy changes to production in a controlled, predictable way.

Basic Branching and Merging:
Let’s go through a simple example of branching and merging with a workflow that you might use in the real world. You’ll follow these steps:
    1. Do some work on a website.
    2. Create a branch for a new user story you’re working on.
    3. Do some work in that branch.

At this stage, you’ll receive a call that another issue is critical and you need a hotfix. You’ll do the following:
    1. Switch to your production branch.
    2. Create a branch to add the hotfix.
    3. After it’s tested, merge the hotfix branch, and push to production.
    4. Switch back to your original user story and continue working.