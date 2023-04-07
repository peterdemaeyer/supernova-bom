# Supernova

Supernova defines a consistent set of principles and standards for projects.

# Features

|Release versions must only depend on release versions. Release versions must thus not depend on any snapshot|
|100% code coverage by default.|
|Dependency management has dependencies of preferred third-party dependencies only.
Individual project may have additional (test) dependencies.|

# Changes

## 1.1.0

* Use `maven-enforcer-plugin` to make sure release versions only depend on release versions.
Snapshots may depend on snapshots.

## 1.0.0

Definition of Supernova standards:

* Common dependencies and versions in `dependencyManagement` section.
* Code coverage must be 100%.
* Flatten poms.

## Principles

Ultimately agile.
Everything must be made with change in mind.
For every imaginable change, there must be a process that supports it, however infrequent.
"We realize this is imperfect, but it's a design choice which is cast in stone" is never an acceptable answer.

Consistency.
A rule which requires fewer exceptions is preferable. 
Taste plays only a minor role in any choice.

Never wonder.
There must be rules for everything, such that one does never have to wonder "how should I do this?"
Should logging statements be in sentence case starting with a capital letter and ending with a full stop?
How should I start the first sentence of my Javadoc?
Never wonder, there are rules for everything.

## Standards

100 % code coverage.
