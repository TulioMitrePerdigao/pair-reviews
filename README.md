# Pair Reviewing
The purpose of this document is to help team members by creating basic guidelines to pair reviewing in Github

## Why should you pair review?
### Knowledge sharing
When the reviewer’s skillset is more expansive than the developer's, there's opportunity to offer improvements, guidance and insights. This is an excellent way to boost a skill you may not be as strong in. In another possible case, the developer in need of a review may be more senior and the reviewer junior. This is a great opportunity for one developer to pass on some wisdom to another. Since the junior might not necessarily be aware of all the intricacies of the code, by asking and trying to understand it, a good review is guaranteed.

### Team interaction
A team with good interaction will always be better at completing their objective. By completing tasks via pair programming and pair reviewing, it's possible to be more familiar with the people you work with, getting to know them and creating a fun working environment.

### Onboarding
Introducing new developers to your team, explaining workflows, processes and the way you’d like to work together can take time. Doing code reviews across the wider team will allow newcomers to meet other developers and also learn about the engineering teams practices without having to go through pages of documentation.

## In which situation should you not pair review?
It's not always efficient to review in pairs.

### WIP
WIP means Work In Progress. It's a bad idea to call for a pair review when one of the members is in the middle of a task. Doing so will hinder their concentration and the time loss from focusing on something else and coming back to a task makes the process inefficient.

### Low complexity
There's no need to spend two developer's time to review a low complexity task. If it's a document change, small configuration changes and refactors, or just a simple task, it's a better idea to have one single person to review.

## Pair Review Checklist

- [ ] Set up a good time to start, so that there's no [wip](#wip).
- [ ] Be sure to write a good pull request before requesting a review/pair review. Check the [PR helpful guidelines here](#how-can-a-pull-request-help-in-the-review-process).
- [ ] Read the pull request together. It's important for both reviewers to understand what is the intention of the task and which value can it generate to the software use cases.
- [ ] Try the main use case "happy" flux - do exactely what's expected for the feature/functionality to work. If it doesn't, transform the pair review session into a pair programming session and finish the task together.
- [ ] Try to find edge cases to the functionality. Test it within the edge and outside it too. Test different input types and look for failures in safeguard for null/undefined inputs.
- [ ] If your feature affects other components and/or multiple features, be sure to test if all of them are still working.
- [ ] Read the code and understand the file changes. Check for code cleanup possibilities and optimizations.

## How can a pull request help in the review process

- Write your task description so that there's no need to bring up Jira tickets when reviewing. If there were any changes to the task, write them up too, so that the product owner and QA testers know what they're looking for.
- How did you test your changes? Include details about environment and automated tests - there's no need to test something an automated process could have done.
- Is there a design prototype to your feature? Is it following the design?
- Are there relevant links to make the review process easier?
- Is there a way to verify your changes visually?

<strong>Thanks for reading! If you wish to contribute to this paper, you can contact me anytime!</strong>
