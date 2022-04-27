```terminal
a@pc terraform % git log --pretty=format:"%h - %an, %ar : %s"  --since=1.week
e217c0c53 - Craig Wright, 15 hours ago : Merge pull request #30938 from jensenbox/patch-1
9b4600cc2 - Ryoh Akiyoshi, 16 hours ago : website: Fix an example for urlencode function
85a081bd2 - Christian Jensen, 18 hours ago : chore: Typo fix
7fe376832 - James Bardin, 18 hours ago : Merge pull request #30931 from hashicorp/jbardin/replace_triggered_by-docs
0501980b4 - James Bardin, 18 hours ago : Update website/docs/language/resources/behavior.mdx
4e95b2402 - James Bardin, 18 hours ago : Update website/docs/language/meta-arguments/lifecycle.mdx
6c15cab21 - James Bardin, 18 hours ago : Update website/docs/language/meta-arguments/lifecycle.mdx
840a7437c - James Bardin, 18 hours ago : Update website/docs/language/meta-arguments/lifecycle.mdx
8089f090f - Sebastian Rivera, 22 hours ago : Merge pull request #30858 from hashicorp/sebasslash/err-approval-input-false
20ba58e82 - Sebastian Rivera, 25 hours ago : CHANGELOG: cloud integration interprets -input flag
9d7fdbea2 - Sebastian Rivera, 2 weeks ago : Handle -input=false in cloud integration
c55707870 - Sebastian Rivera, 26 hours ago : Merge pull request #30917 from hashicorp/sebasslash/config-token-precedence
c7bdd28e4 - Sebastian Rivera, 27 hours ago : CHANGELOG: Token config priority
7b40b3169 - James Bardin, 5 days ago : replace_triggered_by docs
983e40bf4 - Martin Atkins, 2 days ago : CHANGELOG: Remove reference to "go-tfe" library upgrade
465832f1e - Martin Atkins, 2 days ago : Update CHANGELOG.md
09ab872a6 - Martin Atkins, 5 days ago : build: go get github.com/hashicorp/hcl/v2@v2.12.0
84e18f31b - kmoe, 2 days ago : bump mitchellh/cli from 1.1.2 to 1.1.3 (#30914)
1252f8c9c - James Bardin, 5 days ago : Merge pull request #30916 from hashicorp/jbardin/speculative-apply-graph
d9af967a6 - James Bardin, 5 days ago : build a test apply graph during plan
0b784b9b8 - Alisdair McDiarmid, 5 days ago : Merge pull request #30915 from hashicorp/update-metadata-action
955dd6b78 - James Bardin, 5 days ago : update CHANGELOG.md
7da52d94f - James Bardin, 5 days ago : Merge pull request #30900 from hashicorp/jbardin/replace-triggered-by
5ded48e08 - Sebastian Rivera, 5 days ago : Give token in cloud config higher precedence than CLI config file
23dffee56 - Keith Clawson, 7 weeks ago : Always use token in backend config when provided
dd2decf92 - Claire Labry, 5 days ago : change action to pull v1 instead of main
39bbcf2f9 - Klaus Frank, 5 days ago : Fix for newer go version (#30889)
5f58daaf5 - chavacava, 5 days ago : fix typo in struct tag (#30884)
2563bf3f9 - Kevin Wang, 6 days ago : feat: support local preview, post split; add deploy preview (#30814)
7d51ba511 - Sebastian Rivera, 6 days ago : Merge pull request #30862 from hashicorp/update-TF-WORKSPACE-variable
7b6dfabb7 - James Bardin, 6 days ago : Merge pull request #30906 from hashicorp/jbardin/races
e68ad5ec4 - Laura Pacilio, 7 days ago : more edits
912e6ff6d - Laura Pacilio, 7 days ago : Apply suggestions from PR review
a0ebb94fb - Laura Pacilio, 7 days ago : Merge branch 'main' into update-TF-WORKSPACE-variable
2f7aa2fcb - Sebastian Rivera, 7 days ago : Merge pull request #30905 from hashicorp/sebasslash/rename-env-vars
0693c8dfe - James Bardin, 7 days ago : enable the race detector in tests
0731213ec - James Bardin, 7 days ago : sync retry goroutine return
c52e3ed37 - James Bardin, 7 days ago : test fixture race
0fe38fba6 - James Bardin, 7 days ago : prevent unsynchronized output changes access
f63ef2b5e - Sebastian Rivera, 7 days ago : Rename cloud env vars to use TF_CLOUD prefix
1e79682c2 - James Bardin, 7 days ago : minor fixes
art@pc terraform % git log --pretty="%h - %s" --author='Laura Pacilio' --since=1.week
e68ad5ec4 - more edits
912e6ff6d - Apply suggestions from PR review
a0ebb94fb - Merge branch 'main' into update-TF-WORKSPACE-variable
art@pc terraform % git log --pretty=format:"%h - %an, %ar : %s"  --before={2021-10-01} --after={2021-09-01}  --author='Laura Pacilio'
8f09e2759 - Laura Pacilio, 7 months ago : Merge pull request #29567 from drasko95/patch-1
dfbef12a6 - Laura Pacilio, 7 months ago : Merge pull request #29598 from hashicorp/laura-add-mrui-to-sidebar
a8e5b6a4a - Laura Pacilio, 7 months ago : Fix alphabetical order of sidebar
4d1baacea - Laura Pacilio, 7 months ago : Add Machine-Readable UI to sidebar and add hyphen :-)
dcf2d3c1e - Laura Pacilio, 8 months ago : Merge pull request #29494 from magnetikonline/docs-s3-backend-dynamodb-partition-key
43f960b19 - Laura Pacilio, 8 months ago : Merge pull request #28579 from ChadBailey/patch-2
48768a003 - Laura Pacilio, 8 months ago : Merge pull request #29451 from kmadof/patch-1
a819d7db3 - Laura Pacilio, 8 months ago : Merge pull request #29502 from hashicorp/alisdair/json-format-version
3c518880d - Laura Pacilio, 8 months ago : Merge pull request #29509 from drewmullen/d-module-source-revision-option
1e1d47d16 - Laura Pacilio, 8 months ago : Merge pull request #28345 from yvespp/destroy_provisioners_doc
73a3bb270 - Laura Pacilio, 8 months ago : Merge pull request #28334 from paultyng/patch-1
art@pc terraform % git shortlog --since=yesterday.midnight -s --author='Laura Pacilio'
art@pc terraform % git log --before={2021-04-21} --after={2021-04-20} --date=short
commit b649a8ddd118dbd1275faca0cf8a979324a94d6d
Author: Kristin Laemmert <mildwonkey@users.noreply.github.com>
Date:   2021-04-21

    deps: update go-plugin to v1.4.1 (#28465)
    
    + go mod tidy

commit f8493bf5cd78bc2a723f5ddc6f6bceb0e08813ea
Author: James Bardin <j.bardin@gmail.com>
Date:   2021-04-16

    update hcl
    
    update to v2.10.0

commit d15f7394a19f8f4d604b632df54c1d0cc0c9cc85
Merge: fabdf0bea 7f571b5eb
Author: James Bardin <j.bardin@gmail.com>
Date:   2021-04-20

    Merge pull request #28457 from hashicorp/jbardin/provisioner-null-checks
    
    additional null checks in provisioners
art@pc terraform % git show f8493bf5cd78bc2a723f5ddc6f6bceb0e08813ea --stat --pretty=fuller -s
commit f8493bf5cd78bc2a723f5ddc6f6bceb0e08813ea
Author:     James Bardin <j.bardin@gmail.com>
AuthorDate: Fri Apr 16 17:11:27 2021 -0400
Commit:     James Bardin <j.bardin@gmail.com>
CommitDate: Tue Apr 20 17:04:56 2021 -0400

    update hcl
    
    update to v2.10.0
art@pc terraform % history -a
 1050  git hash-object module_2/README.md
 1051  git hash-object module_2/img
 1052  clean
 1053  clear
 1054  git ls-files
 1055  git hash-object module_1/README.md
 1056  git hash-object module_2/README.md
 1057  git hash-object module_2/img/screen_1.png
 1058  git hash-object module_1/img/screen_1.png
 1059  git log --pretty="%h - %s" --author='Laura Pacilio' --since=1.week
 1060  git log --pretty=format:"%h - %an, %ar : %s"  --since=1.week  
 1061  git log --pretty="%h - %s" --author='Laura Pacilio' --since=1.week
 1062  git log --pretty=format:"%h - %an, %ar : %s"  --before={2021-10-01} --after={2021-09-01}  --author='Laura Pacilio'
 1063  git shortlog --since=yesterday.midnight -s --author='Laura Pacilio' 
 1064  git log --before={2021-04-21} --after={2021-04-20} --date=short
 1065  git show f8493bf5cd78bc2a723f5ddc6f6bceb0e08813ea --stat --pretty=fuller -s
art@pc terraform % 
```