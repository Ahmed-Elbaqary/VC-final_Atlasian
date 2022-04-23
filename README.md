This is the final assignment for the course "Version Control with git" from Atlassian on Coursera platform
The task was to create these commits and display its log graph.


ahmed@DESKTOP-VH5ARME:/mnt/e/AI-ITI/Git_Repos/VC final/VC_final_project$ git log --oneline --all --graph
* ebd2662 (feature2) feature 2 wip
*   7bb3666 (develop) Merge branch 'hotfix1' into develop
|\
* \   e940a08 Merge branch 'release1' into develop
|\ \
| | | *   cd9c0d3 (HEAD -> master, tag: v1.01, origin/master) Merge branch 'hotfix1'
| | | |\
| | | |/
| | |/|
| | * | 7a179b6 (hotfix1) fix feature 1 bug Y
| | |/
| | *   bfd2faa (tag: v1.00) Merge branch 'release1'
| | |\
| | |/
| |/|
| * | 689683f fix feature 1 bug X
|/ /
* |   76953db Merge branch 'feature1' into develop
|\ \
| * | 19a2dd9 add feature 1
| * | f10e009 feature 1 wip
|/ /
* / 3ff92e7 add fileA.txt
|/
* fef6e23 add README.md
