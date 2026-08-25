# Actor Interpretation — Problem Statement #04

## Student Project Portfolio & Showcase App

The problem statement explicitly identifies **Student Team** and **Panel Judge** as the target stakeholders/actors.

However, the problem context also states that **the public participates in voting with strict anti-Sybil protections**.

Based on this system behavior, **Public User** has been modeled as an additional actor in the UML use-case diagram.

The reasoning is:

* **Student Team** interacts with the system to create showcase profiles, upload multimedia artifacts, and submit projects.
* **Panel Judge** interacts with the system to view and evaluate submitted projects.
* **Public User** interacts with the system to participate in public voting and view the leaderboard.

Therefore, Public User is included as an additional actor specifically for the voting-related functionality, particularly **UC-06 – Cast Vote** and **UC-07 – View Leaderboard**.

This is an interpretation of the public-voting behavior described in the problem context; Student Team and Panel Judge remain the explicitly listed target stakeholders/actors.
