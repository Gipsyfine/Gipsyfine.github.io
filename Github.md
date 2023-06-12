**create a new repository on the command line**

echo "# Intership" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Gipsyfine/Intership.git
git push -u origin main

**push an existing repository from the command line**

git remote add origin https://github.com/Gipsyfine/Intership.git
git branch -M main
git push -u origin main

1.创建SSH Key

```
ssh-keygen -t rsa -C "youremail@example.com"
```

2.在" C:\Users\gmlea\\.ssh\id_rsa.pub"将 SSH 公钥内容复制到剪贴板

3...在Github找到"Add SSH key"（添加 SSH 密钥）按钮，将新的 SSH 密钥添加到你的 GitHub 帐户。

4.在本地仓库中，使用以下命令将远程仓库的 URL 更改为 SSH 链接：

```powershell
git remote set-url origin git@github.com:<username>/<repository>.git
```

将 `<username>` 替换为你的 GitHub 用户名，`<repository>` 替换为你的仓库名称。

现在，你已经将 GitHub 仓库的推送方式从 HTTPS 更改为 SSH。你可以使用 SSH 链接进行推送和拉取操作，无需提供密码或令牌。确保在进行任何推送操作之前进行测试，以确保 SSH 链接已正确配置

5.`git remote -v` 命令用于显示当前 Git 仓库的远程仓库的详细信息，包括远程仓库的 URL。它显示了远程仓库的名称和对应的 URL，以及该 URL 使用的协议（HTTPS 或 SSH）。这个命令可以帮助你确认远程仓库的配置是否正确，并查看你的本地仓库与远程仓库的关联情况。

6.`ssh -T git@github.com` 命令用于测试 SSH 连接。它尝试建立到 GitHub 的 SSH 连接，并显示连接结果。它主要用于验证你的 SSH 配置是否正确，以及是否能够成功连接到 GitHub。它不会显示与远程仓库的具体关联信息，只是测试连接状态。
