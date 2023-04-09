# Changes

## 2.0.0

* Bumped binary compatibility from Java 1.8 to Java 11.

## 1.1.1

* Fixed bug such that 

## 1.1.0

* Use `maven-enforcer-plugin` to make sure release versions only depend on release versions.
  Snapshots may depend on snapshots.

## 1.0.0

Definition of Supernova standards:

* Common dependencies and versions in `dependencyManagement` section.
* Code coverage must be 100%.
* Flatten poms.
