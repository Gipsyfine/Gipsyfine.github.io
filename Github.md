[GitHub添加SSH密钥](https://blog.csdn.net/adsl624153/article/details/81156436)

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

1. 尝试使用 SSH 链接：如果你已经设置了 SSH 密钥并在 GitHub 上进行了配置，你可以尝试使用 SSH 链接来推送代码。你可以在 GitHub 上查看有关如何设置 SSH 密钥的文档，并将远程仓库链接更改为 SSH 链接。

   ```powershell
   git remote set-url origin git@github.com:Gipsyfine/Intership.git
   ```

   这将把远程仓库链接更改为 SSH 链接。



ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQDF+gXpcjdnS1Zx85B4Fv0uLM6Hjl5YmLGvCzRSml3ZeIgGd66OYXw55dMoniShoFUMJkacWbC27jblxar0JNDQBCeI0E7Xod86tj/Rb1g3ktblCKjpqrrlYaW2H1aTL1URZCRl/dkfzof7sm0Nl7gUeZRVpS+p8HsUHrMAWWqMyuwvj3kYCHu/BoU2zQxYEpNejs/ungXrzwuGNSWKBZjv5lZQITDK2Qq5Rg73w9nEdejTVItHDj/izA7zx0kPYUnwVEiDNKjpzXaPL/HfEvMn3P1PIzk8oHrm8KxHT1zdvJk1j20aYSMVG8JAJs42x1bHItV0JzNb/wH3BhoZO0aJ+/FG6eCqSVcCNOMuk0GyKfnyuY32EfNEbLivE7WZx1rS3dHeTD9PpljBN7wTHl7BxACDPY5AQyDiubCsgsqU8/Lz1nBMatcpSUUNKMBl8Hjmte9QU+EEkYHQBl7Oms4nFNUgYxRIOdcn5POKHp2JFKtTHFa6pKQNC8KNiXncGsgs6ysEr5Hcemtl8ynu1h3xHA6iX6w+f7fT5pJ9V1z/B8hJbBASNLITwQvW2FTmWz4m99jPf6Cpg9kDfYNvm4zHOp+DI4YLmHSn8UtXA641mIkuEVd20TyNakLm7IQzNPj2CZdjywH4ATh2V8IH719lMu0ODB/9fYlrCWAU13yzhQ== gipsyfine@gmail.com