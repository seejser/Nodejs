# Nodejs

## 通过nvm管理Nodejs


1.安装nvm(macOs下使用homebrew)

```
brew install nvm
```

2.添加path

```
cd ~


vim .bash_profile

```

写入：

```
export NVM_DIR=~/.nvm

source $(brew --prefix nvm)/nvm.sh

```

执行：

```
source ./.bash_profile
```

## nvm的使用


```
nvm ls-remote    //查看所以可用的Nodejs版本

nvm install 11.4.0   //下载11.4.0版本


nvm use 11.4.0            //使用11.4.0


nvm alias default 11.4.0       //开机均使用11.4.0





```

## 安装成功的测试


```
node -v


npm -v

```
