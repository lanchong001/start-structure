# IDEA 创建 Maven Java Web 项目
1. IDEA怎样转为 Java Web 项目？
```
  (1).在main目录下，添加webapp目录。
  (2).在webapp目录下，添加WEB-INF目录。
  (3).在WEB-INF目录下，添加web.xml文件。
  IDEA 会自动弹出 Frameworked detected 选项进行配置
```

2. IDEA 怎么创建本地git仓库?
```
 (1).创建.gitignore文件
 
 # Maven #
 target/
 
 # IDEA #
 .idea/
 *.iml
 
 # Eclipse #
 .settings/
 .metadata/
 .classpath
 .project
 Servers/
 
 (2).在IDEA中选择"VCS"菜单,单击"Import into Version Control/Create Git Repository..."
 菜单项,在弹出的对话框中选择项目的根目录,单击"OK"按钮关闭对话框.IDEA就会为我哦么创建一个本地的Git仓库
 
 (3).选择需要提交到git仓库的项目文件
 
 (4).在VCS菜单中单击"Git/Add",添加项目文件
 
 (5).在VCS菜单中单击"Git/Commint Directory..."菜单将代码提交到本地仓库
 
```

3. IDEA 怎么将本地仓库的代码推送到远程仓库?
```
    (1).在IDEA的VCS菜单中单击"Git/Push"菜单即可
```