# FRPrivateRepo
个人 pods 仓库

## 使用说明

```ruby
pod 'AFNetworking', :git => 'https://github.com/xfdev/AFNetworking.git'    
pod 'YYCategories', :git => 'https://github.com/xfdev/YYCategories.git'


```



## 项目链接

[AFNetworking](https://github.com/AFNetworking/AFNetworking)  
[个人Fork](https://github.com/xfdev/AFNetworking)

[YYCategories](https://github.com/ibireme/YYCategories)  
[个人Fork](https://github.com/xfdev/YYCategories)



## 添加其他仓库
### 本仓库在电脑路径

```shell
~/.cocoapods/repos/FRPrivateRepo/
```

### 添加仓库

1. fork 其他仓库；
2. 











### 更新第三方仓库

查看 [fork的YYCategories的版本更新](https://github.com/xfdev/YYCategories#%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0) 。

> 修改仓库代码后，适当的时候要更新版本，并提交到 pod 仓库中以供项目中更新使用。
>
> 1. 修改 `.podspec` 文件中版本号；（修改完之后要添加对应的tag并提交GitHub，才能push第三步。）
> 2. 终端终端定位到项目，输入命令 `pod lib lint` 验证；（出现 `YYCategories passed validation.` 验证通过）
> 3. 提交到Spec Repo，命令 `pod repo push FRPrivateRepo YYCategories.podspec --verbose --allow-warnings` 显示好多警告，最后提交成功，查看仓库中有新的版本号(命令 -- 之后的可不写，避免显示太多的警告)；



