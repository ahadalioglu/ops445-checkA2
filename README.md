# OPS445: Assignment #2 duImproved
# Setup
This will download Assignment 2 locally, allowing you to work on your scripts and upload (push) them back up to GitHub.

1. Clone your assignment repository into your ~/ops445/a2 directory using SSH:
```bash
git clone git@github.com:OPS445-W22/assignment2-yourgithubusername.git ~/ops445/a2/
```

# Submission
1. Run the testing script. You can use this script to run the tests as stated in the Assignment 2 wiki page.  
Please note that this test run script does not check your script docstring or your function docstring.  
```bash
cd ~/ops445/a2/
pwd #confirm that you are in the right directory
python3 ./checkA2.py
```

2. Paste the testing script output into *a2_output.txt*:
```bash
vi ~/ops445/a2/a2_output.txt
```

3. Commit and push (upload) your assignment work:
```bash
git add *
git commit -m "Individual message or note."
git push
```

You can make changes to your scripts and reupload as many times as you like. Make sure you commit+push to do so.

**Note:** Your assignment is automatically submitted at the due date and time using the last published code. Any changes you publish after the due date won't be marked or seen by your professor.
