#Semantic Change Logs v1.0.0-alpha

## Summary

On incrementation of a version number, conduct the following change log.

1. Summary: ##[Flag]|[vX.Y.Z]|[YYYY-MM-DD].
2. Section: A logical part of a project which contains line items.
3. line items: A labeled [Added, Deprecated, Removed, Fixed, Revised, Security] note identifying a change to the project.

##introduction

It was the best of the times... it was the worst of times... Version control has brought sanity to project collaboration. Services such as Github and Bitbucket have brought it to the masses. New technology, methodologies, and powerful frameworks allow us to iterate dramatically.

Version control made sense of it all, a boon to project managers and developers everywhere. Now we're staging, crafting commits, branching and merging, pushing and pulling and thats good! But With the proliferation of version control our beloved change logs are becoming sporadic, almost non existent and thats bad.

Internally anyone intimately involved in a project can navigate the past, present, and future. However externally a poor change log can be harmful to a projects success and not having one at all shows a lack of planning and achievements.

As part of my push for a semantic project structure inspired by [Tom Preston-Werner](http://tom.preston-werner.com/) I propose this simple set of rules and requirements to structure how projects handle their change logs. 

##Semantic Changelog Specification (SemChange)

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in RFC 2119.

1. A CHANGELOG.md file MUST be located within the projects root folder and SHALL be formatted using markdown syntax.

2. The Change log MUST begin with #[Project Name] Change Log.

3. Every version increment MUST add a change log taking the form of summary, section, & line items.

4. A summary MUST flag whether the change log is a Major, Minor, or Patch. 

5. The summary MUST take the form ##[Flag]|[vX.Y.Z]|[YYYY-MM-DD]. For instance Patch | V1.0.1 | 2014-11-02

6. A change log SHOULD provide sections if line items span multiple logical parts of a project. This is indicated by ###Section Name. 

7. Line items are REQUIRED to use only one of the following labels. `ADDED`, `DEPRECATED`, `REMOVED`, `FIXED`, or `REVISED`. A `SECURITY` label MAY be appended if desired.

8. Line items MUST start with a label and SHOULD NOT exceed 1 sentence.

9. Using Semantic Versioning for your project is highly RECOMMENDED.
