# Reflection

**1. Why is 'Squash and Merge' better than a normal merge for small features?**
It turns all the small commits into one clean commit on main. The history stays short and easy to read, and each feature is just one commit.

**2. What is the difference between 'Add single comment' and 'Start a review'? Why does batching matter?**
'Add single comment' sends one comment right away. 'Start a review' saves all your comments and sends them together when you finish. Batching matters because the author gets one notification and one full set of feedback, not multiply emails.

**3. How do Branch Protection Rules stop accidental breakage?**
They stop people from pushing straight to main. Every change needs a Pull Request and at least one approval first, so someone else checks the code before it goes in.

**4. Why merge origin/main into your branch locally instead of forcing a push?**
Merging lets you see the conflict and pick what to keep, and it only adds a new commit, so nothing is lost. A force push can erase other people's work. Merging also keeps the same PR and its comments.
