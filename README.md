# GitStatus

![Icon][0]


If you are maintaining multiple projects that use git and often need to switch between several projects, you may forget which branch a repo is currently in;

Or you may forget to commit some modifications after a day's work.

In fact, the above problem has often been encountered in my recent work, so I tried to write this App to solve it.

It can monitor the status of multiple repos at the same time, and then prompt you in the menu bar.
*  Is there any repo code that has not been submitted?
*  Is there a repo? The current branch is a stable branch rather than a dev branch.(e.g., master, release)


## Usage：

* The runtime menu bar will display `SC` `S` representing safe, that is, all repo are in the non-stable branch; `C` representing clean, that is, all repo code has been submitted. Any repo in the stable branch `S` will display red, and any repo in the unclean state `C` will display red.。

![Menu][1]

* Click the menu bar to enter the repo addition interface, where you can add multiple repos.

![Add repo][2]

* Click the branch in the lower right corner of the repo list to enter the stable branch setting page and manually set the stable branch of the repo (such as master, release and other branches that should not stay for a long time)

![Add a stable branch][3]

  [0]: https://github.com/github-xiaogang/GitStatus/blob/master/readme/icon.png
  [1]: https://github.com/github-xiaogang/GitStatus/blob/master/readme/menubar.png
  [2]: https://github.com/github-xiaogang/GitStatus/blob/master/readme/repo.png
  [3]: https://github.com/github-xiaogang/GitStatus/blob/master/readme/stable.png
