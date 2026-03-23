Pull/Push/Merge conflict exercise:

Basic workflow

1： ALWAYS REMEMBER TO **FETCH ORIGIN/PULL** FIRST!!!! This makes you get the latest updated version of the repository.

2：Create a new .txt file in this repository and name it by your name. Then push it to the repository.

3：Check if your updated file is shown in the repo.



Merge conflict:

This is a common mistake people encountered as a beginner. The reason for this conflict is that you didn't pull first and updated the repository. In the meantime, you push somesomething to the repository for the same part of the code. Thus, github doesn't know which version he should adapt. In this case github will provide you the conflict details and asked you to solve this conflict. You can pick one version or just combine two versions and then solve this conflic.



Two people changed the same part of a file, based on different versions



Scenario:

Everyone starts from the same version

Person A edits line 5 -> pushes

Person B also edited line 5 earlier



Now:



B tries to push ->  conflict

OR B pulls -> conflict appears during pull

So what actually caused it?

The real cause is:



“You edited an outdated version of the same content someone else changed”



If B had pulled first → they would see A’s change

Then B wouldn’t overwrite the same line



Practice:

1: In Merge\_Conflict.txt, change the same line: What is your favorite sport?

Then one person push first.







I AM REYNOLDS LI

