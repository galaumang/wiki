# Git -- Best Practices

## **Git Commit Message** 

There are two main components of a Git commit message: the title or summary, and the description. The commit message title is limited to 72 characters, and the description has no character limit. While those are the established character limits, most developers suggest that the commit message summary be no longer than 50 characters, and the description be limited to 72. 

Ultimately, the trick to structuring an exceptional commit message is to find the proper balance between brevity and detail. Brief enough that it's easy to read, but detailed enough that it's easy to understand. 

There are a few things you can do to improve your Git commit messages right off the bat: 
* Avoid unnecessary capitalization 
* Double check your spelling
* Don't end commit message summaries with punctuation 

Abiding by these simple guidelines makes it easier to search and filter commits, as well as simply making your repository look more visually appealing. 

The best way to structure your commit message is to prefix the message with specific commit type along reference to issue # being address in the commit, if any. Using this approach, makes easy for project contributors to filter and serach for specific commit.

**Example**
```
feat: add serach api (#18)                                 <-- commit summary
new search api to return the results for specific input    <-- commit description
```

### **Commit types**
* feat - Feature
* fix - Bug fixes
* docs - changes to the documentation
* style - style or formatting change
* test - test a feature and/or bug
* perf - improve code performance
* config - project or other configuration changes
* misc - refactoring the project, etc
