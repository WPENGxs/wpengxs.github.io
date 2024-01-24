<!-- 
 * @Author: Peng Wang
 * @Description: 帮助文档，旨在让不了解网站框架的人更新网站内容
-->

## 帮助文档

### 如何更新/about下的News
请在```/_news```下新建.md文件，无文件名要求，内容为：
```
---
layout: post
date: date (eg. Oct 1, 2024)
inline: true
---

your context
```

### 如何更新/committee中的人员
#### 添加学术委员会成员
请在```/_cacad```中新建.md文件，文件名不限
md文件中内容为
```
---
name: meow meow # 成员名
university: meow university # 成员的所属学校
num_en: First # 成员所属的委员会届数英文
num: 1 # 成员所属的委员会届数数字，用于成员的定位
img: cat.jpeg # 成员的照片，比例为1:1最佳，照片请上传至/assets/img
---
```
#### 添加秘书处成员
请在```/_csecr```中新建.md文件，文件名不限
md文件中内容为
```
---
name: meow meow # 成员名
university: meow university # 成员的所属学校
num_en: First # 成员所属的委员会届数英文
num: 1 # 成员所属的委员会届数数字，用于成员的定位
img: cat.jpeg # 成员的照片，比例为1:1最佳，照片请上传至/assets/img
---
```
#### 删除成员
将对应位置的.md文档删除即可

### 更新/activities中的活动
#### 更新左上的标签
请在```/_page/activities.md```中的```all_tags```数组中添加标签即可
#### 更新分页的活动数量
请修改```/_layout/activities.html```中的```var itemsPerPage = 你想每页展示的项数;```即可
#### 添加活动
请在```/_activities```目录下新建.md文件，内容为
```
---
name: new live test
date: 2024-10-10 # 活动时间 yyyy-mm-dd

img: mlnlp.jpg # 活动卡照片，照片请上传至/assets/ac_img
href: https://github.com/MLNLP-World # 点击跳转的链接
title: mlnlp_test # 活动名称
people: Libo Qin, Meoww Meow # 活动人员
detail: This is detail # 描述文字
tags: ['nlp'] # 该活动的Tag
---
```
注意：活动通过读取date排序，为时间降序排列


### 更新/projects中的repo
由于我使用的[GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats/blob/master/docs/readme_cn.md)无法统计组织的信息，目前只能通过手动添加的方式完善projects中的Github Repositories，开发者的[Top Issues Dashboard](https://github.com/anuraghazra/github-readme-stats/issues/1935)有列出该项计划。如果后面有更新到自动统计组织的Repos，再更新网站的该功能。
#### 添加
请在```/_pages/projects.md```中的```repos```数组中添加Github Repos名称即可
