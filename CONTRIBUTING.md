# Contributing

Please take a moment to review this document in order to make the contribution process easy and 
effective for everyone involved.

Following these guidelines helps to communicate that you respect the time of the developers managing 
and developing this open source repo. In return, they should reciprocate that respect in addressing 
your issue or assessing your pull requests.

## Goal

The repository is meant to work as a learning tool for new programmers and also as a cheat sheet for 
other intermediate developers. The repository is dedicated to python and also coding in general.

## Using the Issue Tracker

The issue tracker is the preferred channel for bug reports, adding content and submitting pull requests, but please 
respect the following restrictions:
* Please do not use the issue tracker for personal support requests. If you need any help in understanding 
the content or code of any specific file, contact the creator of the file, preferably via email.
* Please do not derail or troll issues. Keep the discussion on topic and respect the opinion of others.

## Adding and Requesting content

The [README](https://github.com/aceking007/Byte-Sized-Code/blob/master/README.md) file contains a checklist 
for content that is prepared and content that is to be prepared. Do add to the checklists (and also raise an issue) 
if you want a notebook on some specific topic or feel free to work on some of the unchecked topics by creating a 
self-explanatory jupyter notebook. 

Please **do** raise an issue before working on a specific topic. This prevents multiple people from working individually on a 
single topic. Feel free to contribute in groups to a single notebook. This encourages community participation and reduces 
the amount of workload or stress on a single person.

## Bug Reports

A bug is a *demonstrable problem* that is caused by the code in the repository.  
Good bug reports are extremely helpful - thank you!

Guidelines for bug reports:
1. **Use the GitHub issue search** - check if the issue has already been reported.
2. **Check if the issue has been fixed** - try to reproduce it using the latest master or development branch in the repo.
3. **Isolate the problem** - make sure that the code in the repository is *definitely* responsible for the issue.

A good bug report shouldn't leave others needing to chase you up for more information.  
Please try to be as detailed as possible in your report.

## Pull Requests

Good pull requests - patches, improvements, new features - are a fantastic help. They should remain 
focused in scope and avoid containing unrelated commits.

**Please ask first** before embarking on any significant pull request (e.g. code refactoring, adding examples or files), 
otherwise you risk spending a lot of time working on something that the developers might not want to merge into the project.  
Please adhere to the coding conventions used throughout the project (indentation, comments, etc.).

Adhering to the following process is the best way to get your work merged:

1. [Fork](https://help.github.com/fork-a-repo) the repo, clone your fork, and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/<repo-name>
   # Navigate to the newly cloned directory
   cd <repo-name>
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/<upsteam-owner>/<repo-name>
   ```

2. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout <dev-branch>
   git pull upstream <dev-branch>
   ```

3. Create a new topic branch (off the main project development branch) to
   contain your feature, change, or fix:

   ```bash
   git checkout -b <topic-branch-name>
   ```

4. Commit your changes in logical chunks. Please adhere to these [git commit
   message guidelines](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
   or your code is unlikely be merged into the main project. Use Git's
   [interactive rebase](https://help.github.com/articles/interactive-rebase)
   feature to tidy up your commits before making them public.

5. Locally merge (or rebase) the upstream development branch into your topic branch:

   ```bash
   git pull [--rebase] upstream <dev-branch>
   ```

6. Push your topic branch up to your fork:

   ```bash
   git push origin <topic-branch-name>
   ```

10. [Open a Pull Request](https://help.github.com/articles/using-pull-requests/)
    with a clear title and description.


## License

Any code/documentation that you contribute to the project will be available as open-source under the MIT License.

## Credits

The above document was adapted from the [contributing doc](https://github.com/roots/guidelines/blob/master/CONTRIBUTING.md) of the [roots](https://github.com/roots) project.