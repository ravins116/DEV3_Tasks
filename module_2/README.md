# Module_1
## First [issue](#1) tasks
- [x] **Create [repo](/ravins116/DEV3_Tasks) in Github**
- [x] **Get Git in workstation**
- [x] **Get IDE in workstation**

## Screenshots
![Get Git in workstation](/module_1/img/screen_1.png)
![Get IDE in workstation](/module_1/img/screen_2.png)

# Module_2

## Workflow
- [x] cp -a module_1/. module_2 

![Compare hashes](/module_2/img/screen_3.png)
### Git terraform activities 1.week
- [x] git shortlog --since=1.week 
- [x]  git log --pretty=format:"%h - %an, %ar : %s"  --since=1.week  
- [x] git log --pretty=format:"%h - %an, %ar : %s"  --before={2022-04-27} --after={2022-04-20} 
- [x] git rev-list --since=1.week --all --format=short
### Git terraform Contribute commits 1.week
- [x] git shortlog --since=1.week -s --author='Laura Pacilio'
- [x] git log --pretty="%h - %s" --author='Laura Pacilio' --since=1.week
- [x] Answer: yes, there was commits

### Git terraform Contribute commits 2021 september 
- [x] git shortlog  -s --author='Laura Pacilio' --before={2021-10-01} --after={2021-09-01} 
- [x] git log --pretty=format:"%h - %an, %ar : %s"  --before={2021-10-01} --after={2021-09-01}  --author='Laura Pacilio'
- [x] Answer: yes, there was commits

### Git terraform Contribute commits yesterday
- [x] git shortlog --since=yesterday.midnight -s --author='Laura Pacilio' 
- [x] Answer: no, there no commits

### Git terraform Contribute commits 2021.04.16
- [x] git log --before={2021-04-21} --after={2021-04-20} --date=short
- [x] git show f8493bf5cd78bc2a723f5ddc6f6bceb0e08813ea --stat --pretty=fuller -s
- [x] there was commit. maybe because cherry-picked commit from a different branch or something was done, than commit changed date.

### terminal workflow
- [x] terminal [history](/module_2/terminal.md)

## Contribute
[![ravins116](https://contrib.rocks/image?repo=ravins116/DEV3_Tasks)**Artūrs**](https://github.com/ravins116/DEV3_Tasks/graphs/contributors)