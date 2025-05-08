+++
date = '2025-05-08T20:02:48+08:00'
draft = true
title = 'My First Post'
+++


### 環境設定

使用前需安裝

- [Git](https://git-scm.com/downloads) 
- [HUGO](https://gohugo.io/installation/)　

#### 安裝 HUGO



#### [Windows](https://gohugo.io/installation/windows/)

```bash=
scoop install hugo-extendsd
```

#### [macOS](https://gohugo.io/installation/macos/)

```bash=
sudo port install hugo
```

#### [Linux](https://gohugo.io/installation/linux/)

```bash=
sudo apt install hugo
```

### 快速開始

確認 HUGO 版本
```bash=
hugo version
```



想把檔案放在哪，就在那輸入

```bash=
hugo new site 你想要的資料夾名稱 
cd 資料夾名稱
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml

```

