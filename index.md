### 用例名称：Options详细用例
### 用例说明
管理员在进入Settings后，在Options中可以进行修改仓库名、用模板建立新的仓库，编辑仓库的社交媒体预览。还可以对特征进行修改，例如从GitHub Free升级到GitHub Pro、设置问题模板等。管理员还可以设置合并按钮，就是合并拉取请求时，可以允许合并提交，压缩或变基的任何组合，合并拉取请求后，可以自动删除头分支。管理员创建源代码档案时，可以选择在档案中使用Git LFS存储的文件。最后，管理员可以对仓库进行修改仓库可见性、转让仓库、存档备份仓库以及删除仓库。

### 参与者：管理员
### 元素
Options、Settings、Rename、Template repository、Social preview、Edit、Features、Wikis、Issues、Sponsorships、Projects、Upgrade、Set up templates、Set up sponsor button、Data services、Merge button、Allow merge commits、Allow squash merging、Allow rebase merging、Automatically delete head branches、Archives、Include Git LFS objects in archives、GitHub Pages、Upgrade、make this repository public to enable Pages、Danger Zone、Change repository visibility、Transfer ownership、Archive this repository、Delete this repository
### 关系
管理员对Options是关联关系
Settings、Data services、Merge button、Danger Zone对Options是包含关系
Features、Merge button、Archives、GitHub Pages对Options是扩展关系
Social preview对Settings是包含关系
Rename、Template repository对Settings是扩展关系
Edit对Social preview是包含关系
Wikis、Issues、Sponsorships、Projects对Features是包含关系
Upgrade对Wikis是扩展关系
Set up templates对Issues是扩展关系
Set up sponsor button对Sponsorships是扩展关系
Allow merge commits、Allow squash merging、Allow rebase merging对Merge button是泛化关系
Automatically delete head branches对Merge button是扩展关系
Include Git LFS objects in archives对Archives是包含关系
Upgrade、make this repository public to enable Pages对GitHub Pages是包含关系
Change repository visibility、Transfer ownership、Archive this repository、Delete this repository对Danger Zone是包含关系
### 建模思路
1.管理员在Settings中可以进行修改仓库名Rename、模板建立仓库Template repository 、设置预览仓库界面Social preview操作。对Social preview还可以进行编辑Edit操作。
2.管理员在Features中有设置Wikis、Issues、Sponsorships、Projects操作，分别对其进行修改、添加的操作。
3.管理员在Data services操作中，对数据服务进行管理。
4．管理员用Merge button操作设置合并按钮，泛化出Allow merge commits、Allow squash merging、Allow rebase merging三个操作，还有Automatically delete head branches操作自动删除头分支。
5.管理员用Archives操作创建源代码档案。Include Git LFS objects in archives操作是管理员在创建的过程中使用Git LFS存储的文件。
6.管理员的Danger Zone操作，是对仓库进行一些会彻底改变仓库的属性的操作。比如Change repository visibility操作修改仓库可见性、Transfer ownership操作转让仓库、Archive this repository操作存档备份仓库、Delete this repository操作删除仓库。
