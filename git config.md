#git config

git的全局配置，存储于$HOME/.gitconfig里，这里的配置影响当前用户的所有git repo。

命令行里，通过`git config的--global`参数开启全局配置。

###基本配置

>$: git config --global user.name ""
>
>$: git config --global user.email ""
>
>$:git config --global github.user USERNAME 
>
>$:git config --global github.token TOKEN

####默认编辑器

>$: git config --global core.editor vim   

####默认merge/diff工具

###Repo级别的配置

repo级别的配置，存储在仓库目录的.git/config文件中。这里的所有配置项跟全局一致，可以覆盖全局信息。

