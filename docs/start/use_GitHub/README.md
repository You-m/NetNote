# GitHub 使用方法

> [Git教程 - 廖雪峰的官方网站](https://www.liaoxuefeng.com/wiki/896043488029600)

## 从主库创建拉取请求

![GitHub01](./img/github-01.jpg)
![GitHub02](./img/github-02.jpg)
![GitHub03](./img/github-03.jpg)
![GitHub04](./img/github-04.jpg)
![GitHub05](./img/github-05.jpg)

### VScode 拉取到本地

  ![GitHub06](./img/github-06.jpg)

### IDEA 拉取到本地

  ![GitHub07](./img/github-07.jpg)

## 推送本地更改到主库

### [推送之前先拉取](#从主库创建拉取请求)

 ![GitHub08](./img/github-08.jpg)

### 推送到远程仓库

 ![GitHub09](./img/github-09.jpg)
 ![GitHub10](./img/github-10.jpg)
 ![GitHub11](./img/github-11.jpg)

### 向主库提交拉取请求

 ![GitHub12](./img/github-12.jpg)
 ![GitHub13](./img/github-13.jpg)
 ![GitHub14](./img/github-14.jpg)

## 使用 GitHub CLI

:::tip
**命令行界面**（英语：**command-line interface**，缩写：CLI）是在图形用户界面得到普及之前使用最为广泛的用户界面，它通常不支持鼠标，用户通过键盘输入指令，计算机接收到指令后，予以执行。
也有人称之为 **字符用户界面**（CUI）。

前往[下载 GitHub CLI](https://cli.github.com/) 并安装。

推荐在 PowerShell 中使用 GitHub CLI。
:::

### 登入

使用以下指令登入到 GitHub：

```sh
gh auth login
```

1. 选择 `GitHub.com` 
2. 选择 `Login with a web browser`（通过浏览器登入）
3. 按下 <kbd>Enter</kbd> 键，将打开浏览器，将 `one-time code` 粘贴进去：
   ![cli-00](./img/cli-00.jpg)
   浏览器操作完后，回到 PowerShell 按下 <kbd>Enter</kbd> 键
4. 选择 Git 协议为 `SSH`
5. 登入成功！

```text {2,6,10,11,15}
? What account do you want to log into?  [Use arrows to move, type to filter]
> GitHub.com
  GitHub Enterprise Server

? How would you like to authenticate?  [Use arrows to move, type to filter]
> Login with a web browser
  Paste an authentication token

! First copy your one-time code: FFFF-FFFF
- Press Enter to open github.com in your browser...
✓ Authentication complete. Press Enter to continue...

? Choose default git protocol  [Use arrows to move, type to filter]
  HTTPS
> SSH

✓ Logged in as Yue-plus
```

### 常用指令



### 常规操作

#### 从主库拉取

#### 推送到主库