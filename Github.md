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

1.����SSH Key

```
ssh-keygen -t rsa -C "youremail@example.com"
```

2.��" C:\Users\gmlea\\.ssh\id_rsa.pub"�� SSH ��Կ���ݸ��Ƶ�������

3...��Github�ҵ�"Add SSH key"����� SSH ��Կ����ť�����µ� SSH ��Կ��ӵ���� GitHub �ʻ���

4.�ڱ��زֿ��У�ʹ���������Զ�ֿ̲�� URL ����Ϊ SSH ���ӣ�

```powershell
git remote set-url origin git@github.com:<username>/<repository>.git
```

�� `<username>` �滻Ϊ��� GitHub �û�����`<repository>` �滻Ϊ��Ĳֿ����ơ�

���ڣ����Ѿ��� GitHub �ֿ�����ͷ�ʽ�� HTTPS ����Ϊ SSH�������ʹ�� SSH ���ӽ������ͺ���ȡ�����������ṩ��������ơ�ȷ���ڽ����κ����Ͳ���֮ǰ���в��ԣ���ȷ�� SSH ��������ȷ����

5.`git remote -v` ����������ʾ��ǰ Git �ֿ��Զ�ֿ̲����ϸ��Ϣ������Զ�ֿ̲�� URL������ʾ��Զ�ֿ̲�����ƺͶ�Ӧ�� URL���Լ��� URL ʹ�õ�Э�飨HTTPS �� SSH�������������԰�����ȷ��Զ�ֿ̲�������Ƿ���ȷ�����鿴��ı��زֿ���Զ�ֿ̲�Ĺ��������

6.`ssh -T git@github.com` �������ڲ��� SSH ���ӡ������Խ����� GitHub �� SSH ���ӣ�����ʾ���ӽ��������Ҫ������֤��� SSH �����Ƿ���ȷ���Լ��Ƿ��ܹ��ɹ����ӵ� GitHub����������ʾ��Զ�ֿ̲�ľ��������Ϣ��ֻ�ǲ�������״̬��
