# clevertecGitCourse

копия работы в командной строке git



user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec
$ git init
Initialized empty Git repository in E:/новая для сохранения/java/Clevertec/.git/

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git add .gitignore

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git add project.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore
        new file:   project.txt


user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git commit -m "this is a fully working project"
[master (root-commit) e914fe0] this is a fully working project
 2 files changed, 2 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 project.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git remote add origin https://github.com/AnastasiyaIlkevich/clevertecGitCourse.git

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git remote -v
origin  https://github.com/AnastasiyaIlkevich/clevertecGitCourse.git (fetch)
origin  https://github.com/AnastasiyaIlkevich/clevertecGitCourse.git (push)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git tag 0.1

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git push origin master 0.1
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 315 bytes | 315.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/AnastasiyaIlkevich/clevertecGitCourse.git
 * [new branch]      master -> master
 * [new tag]         0.1 -> 0.1

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git branch develop

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git checkout develop
Switched to branch 'develop'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git branch -a
* develop
  master
  remotes/origin/master

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git add project_develop_first_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git commit -m "feat: develop first commit"
[develop cfe362b] feat: develop first commit
 1 file changed, 1 insertion(+)
 create mode 100644 project_develop_first_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git add project_develop_second_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git commit -m "feat: develop second commit"
[develop 137132e] feat: develop second commit
 1 file changed, 1 insertion(+)
 create mode 100644 project_develop_second_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git commit -m "feat: develop second commit"
On branch develop
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        project_develop_third_commit.txt

nothing added to commit but untracked files present (use "git add" to track)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git add project_develop_second_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git commit -m "feat: develop second commit"
On branch develop
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        project_develop_third_commit.txt

nothing added to commit but untracked files present (use "git add" to track)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git status
On branch develop
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        project_develop_third_commit.txt

nothing added to commit but untracked files present (use "git add" to track)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git add project_develop_third_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git status
On branch develop
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   project_develop_third_commit.txt


user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git commit -m "feat: develop third commit"
[develop 619840a] feat: develop third commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 project_develop_third_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git branch feature_1

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git branch feature_2

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git checkout feature_2
Switched to branch 'feature_2'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_2)
$ git add feature2_first_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_2)
$ git status
On branch feature_2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   feature2_first_commit.txt


user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_2)
$ git commit -m "feat: feature_2 first commit"
[feature_2 191468c] feat: feature_2 first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature2_first_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_2)
$ git add feature2_second_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_2)
$ git commit -m "feat: feature_2 second commit"
[feature_2 e656712] feat: feature_2 second commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature2_second_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_2)
$ git add feature2_third_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_2)
$ git commit -m "feat: feature_2 third commit"
[feature_2 6d22bab] feat: feature_2 third commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature2_third_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_2)
$ git add feature2_fourth_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_2)
$ git commit -m "feat: feature_2 fourth commit"
[feature_2 e260dec] feat: feature_2 fourth commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature2_fourth_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_2)
$ git checkout feature_1
Switched to branch 'feature_1'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_1)
$ git add feature1_first_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_1)
$ git commit -m "feat: feature_1 first commit"
[feature_1 92fcc01] feat: feature_1 first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature1_first_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_1)
$ git add feature1_second_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_1)
$ git commit -m "feat: feature_1 second commit"
[feature_1 79695b9] feat: feature_1 second commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature1_second_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_1)
$ git log
commit 79695b935f9a0cc5d3ccb0ccdeb911a6911961b6 (HEAD -> feature_1)
Author: AnastasiyaIlkevich <sirin199@yandex.ru>
Date:   Sun Feb 5 15:07:06 2023 +0300

    feat: feature_1 second commit

commit 92fcc01efdbcc9dace2bef55589207efebf3e2f1
Author: AnastasiyaIlkevich <sirin199@yandex.ru>
Date:   Sun Feb 5 15:06:39 2023 +0300

    feat: feature_1 first commit

commit 619840a13f1de7b717253d9d512fa617ccf18f12 (develop)
Author: AnastasiyaIlkevich <sirin199@yandex.ru>
Date:   Sun Feb 5 15:02:33 2023 +0300

    feat: develop third commit

commit 137132ef1d678a44cde6462526780dd8afe6063e
Author: AnastasiyaIlkevich <sirin199@yandex.ru>
Date:   Sun Feb 5 15:00:35 2023 +0300

    feat: develop second commit

commit cfe362b33c7e2969f7092ebb26547063c6cb3e9b
Author: AnastasiyaIlkevich <sirin199@yandex.ru>
Date:   Sun Feb 5 14:59:36 2023 +0300

    feat: develop first commit

commit e914fe02ca1e53a8721c896d9a34db561dfd71cb (tag: 0.1, origin/master, master)
Author: AnastasiyaIlkevich <sirin199@yandex.ru>
Date:   Sun Feb 5 14:56:46 2023 +0300

    this is a fully working project

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_1)
$ git add feature1_third_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_1)
$ git commit -m "feat: feature_1 third commit"
[feature_1 5d147d3] feat: feature_1 third commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature1_third_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (feature_1)
$ git checkout develop
Switched to branch 'develop'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git branch -a
* develop
  feature_1
  feature_2
  master
  remotes/origin/master

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git add project_develop_fourth_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git commit -m "feat: develop fourth commit"
[develop cd524bb] feat: develop fourth commit
 1 file changed, 1 insertion(+)
 create mode 100644 project_develop_fourth_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git checkout master
Switched to branch 'master'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git branch hotfixes

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git checkout hotfixes
Switched to branch 'hotfixes'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (hotfixes)
$ git status
On branch hotfixes
nothing to commit, working tree clean

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (hotfixes)
$ git add project.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (hotfixes)
$ git commit -m "fix: hotfixes - fixbug"
[hotfixes b8026ef] fix: hotfixes - fixbug
 1 file changed, 3 insertions(+), 1 deletion(-)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (hotfixes)
$ git checkout master
Switched to branch 'master'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git branch -a
  develop
  feature_1
  feature_2
  hotfixes
* master
  remotes/origin/master

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git merge hotfixes
Updating e914fe0..b8026ef
Fast-forward
 project.txt | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git tag 2.0

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ ^C

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git push origin master 0.2
error: src refspec 0.2 does not match any
error: failed to push some refs to 'https://github.com/AnastasiyaIlkevich/clevertecGitCourse.git'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git tag 0.2

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git push origin master 0.2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/AnastasiyaIlkevich/clevertecGitCourse.git
   e914fe0..b8026ef  master -> master
 * [new tag]         0.2 -> 0.2

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git checkout develop
Switched to branch 'develop'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git merge hotfixes
Merge made by the 'recursive' strategy.
 project.txt | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git branch -d hotfixes
Deleted branch hotfixes (was b8026ef).

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git checkout develop
Already on 'develop'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git merge feature_1
Merge made by the 'recursive' strategy.
 feature1_first_commit.txt  | 0
 feature1_second_commit.txt | 0
 feature1_third_commit.txt  | 0
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature1_first_commit.txt
 create mode 100644 feature1_second_commit.txt
 create mode 100644 feature1_third_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git branch -d feature_1
Deleted branch feature_1 (was 5d147d3).

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git branch release

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git checkout release
Switched to branch 'release'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git status
On branch release
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   project_develop_first_commit.txt
        modified:   project_develop_fourth_commit.txt
        modified:   project_develop_second_commit.txt
        modified:   project_develop_third_commit.txt

no changes added to commit (use "git add" and/or "git commit -a")

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git add project_develop_first_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git commit -m "test: release - testing_1.0"
[release 72b14aa] test: release - testing_1.0
 1 file changed, 4 insertions(+), 1 deletion(-)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git add project_develop_second_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git commit -m "test: release - testing_2.0"
[release 3af7466] test: release - testing_2.0
 1 file changed, 4 insertions(+), 1 deletion(-)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git status
On branch release
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   project_develop_fourth_commit.txt

no changes added to commit (use "git add" and/or "git commit -a")

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git diff
diff --git a/project_develop_fourth_commit.txt b/project_develop_fourth_commit.txt
index 8b13789..e69de29 100644
--- a/project_develop_fourth_commit.txt
+++ b/project_develop_fourth_commit.txt
@@ -1 +0,0 @@
-

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git status
On branch release
nothing to commit, working tree clean

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git checkout develop
Switched to branch 'develop'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git merge release
Updating 508d64b..3af7466
Fast-forward
 project_develop_first_commit.txt  | 5 ++++-
 project_develop_second_commit.txt | 5 ++++-
 2 files changed, 8 insertions(+), 2 deletions(-)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git checkout release
Switched to branch 'release'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git add project_develop_third_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git commit -m "test: release - testing_3.0"
[release 966c072] test: release - testing_3.0
 1 file changed, 1 insertion(+)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git add project_develop_fourth_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git commit -m "test: release - testing_4.0"
[release b254f97] test: release - testing_4.0
 1 file changed, 1 insertion(+), 1 deletion(-)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git checkout master
Switched to branch 'master'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git merge release
Updating b8026ef..b254f97
Fast-forward
 feature1_first_commit.txt         | 0
 feature1_second_commit.txt        | 0
 feature1_third_commit.txt         | 0
 project_develop_first_commit.txt  | 4 ++++
 project_develop_fourth_commit.txt | 1 +
 project_develop_second_commit.txt | 4 ++++
 project_develop_third_commit.txt  | 1 +
 7 files changed, 10 insertions(+)
 create mode 100644 feature1_first_commit.txt
 create mode 100644 feature1_second_commit.txt
 create mode 100644 feature1_third_commit.txt
 create mode 100644 project_develop_first_commit.txt
 create mode 100644 project_develop_fourth_commit.txt
 create mode 100644 project_develop_second_commit.txt
 create mode 100644 project_develop_third_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git tag 0.3

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git push origin master 0.3
Enumerating objects: 35, done.
Counting objects: 100% (35/35), done.
Delta compression using up to 8 threads
Compressing objects: 100% (29/29), done.
Writing objects: 100% (33/33), 2.98 KiB | 610.00 KiB/s, done.
Total 33 (delta 15), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (15/15), done.
To https://github.com/AnastasiyaIlkevich/clevertecGitCourse.git
   b8026ef..b254f97  master -> master
 * [new tag]         0.3 -> 0.3

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git checkout develop
Switched to branch 'develop'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git merge release
Updating 3af7466..b254f97
Fast-forward
 project_develop_fourth_commit.txt | 2 +-
 project_develop_third_commit.txt  | 1 +
 2 files changed, 2 insertions(+), 1 deletion(-)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git branch -d release
Deleted branch release (was b254f97).

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git push origin develop
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'develop' on GitHub by visiting:
remote:      https://github.com/AnastasiyaIlkevich/clevertecGitCourse/pull/new/develop
remote:
To https://github.com/AnastasiyaIlkevich/clevertecGitCourse.git
 * [new branch]      develop -> develop

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git merge feature_2
Merge made by the 'recursive' strategy.
 feature2_first_commit.txt  | 0
 feature2_fourth_commit.txt | 0
 feature2_second_commit.txt | 0
 feature2_third_commit.txt  | 0
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature2_first_commit.txt
 create mode 100644 feature2_fourth_commit.txt
 create mode 100644 feature2_second_commit.txt
 create mode 100644 feature2_third_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git branch -d feature_2
Deleted branch feature_2 (was e260dec).

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git push origin develop
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 8 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (10/10), 1.12 KiB | 575.00 KiB/s, done.
Total 10 (delta 5), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (5/5), completed with 1 local object.
To https://github.com/AnastasiyaIlkevich/clevertecGitCourse.git
   b254f97..fcaeee7  develop -> develop

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git branch release

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git checkout release
Switched to branch 'release'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git add project.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git commit -m "test: release - full_testing"
[release f36d574] test: release - full_testing
 1 file changed, 3 insertions(+), 1 deletion(-)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git tag 0.4

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (release)
$ git checkout master
Switched to branch 'master'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git merge release
Updating b254f97..f36d574
Fast-forward
 feature2_first_commit.txt  | 0
 feature2_fourth_commit.txt | 0
 feature2_second_commit.txt | 0
 feature2_third_commit.txt  | 0
 project.txt                | 4 +++-
 5 files changed, 3 insertions(+), 1 deletion(-)
 create mode 100644 feature2_first_commit.txt
 create mode 100644 feature2_fourth_commit.txt
 create mode 100644 feature2_second_commit.txt
 create mode 100644 feature2_third_commit.txt

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git push origin master 0.4
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 325 bytes | 325.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/AnastasiyaIlkevich/clevertecGitCourse.git
   b254f97..f36d574  master -> master
 * [new tag]         0.4 -> 0.4

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (master)
$ git checkout develop
Switched to branch 'develop'

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git merge release
Updating fcaeee7..f36d574
Fast-forward
 project.txt | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git branch -d release
Deleted branch release (was f36d574).

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$ git push origin develop
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/AnastasiyaIlkevich/clevertecGitCourse.git
   fcaeee7..f36d574  develop -> develop

user@HOME-PC MINGW64 /e/новая для сохранения/java/Clevertec (develop)
$
