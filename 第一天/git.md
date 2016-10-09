## ����git������˺�
```
git config --global user.name
git config --global user.email
```
- �鿴����
git config --list
## ����Ŀ¼
```
mkdir Ŀ¼������
```

## �ı�Ŀ¼
```
cd ..
```
# locals
## git init
��ʼ�����زֿ⣬��ʾ��ǰ�ļ��й�git������

## echo�����������ݲ��Ҵ����ļ�
```
echo hello > index.txt
```

## �鿴�ļ�������
```
cat �ļ���
```
## �༭
```
vi index.txt
```
> �Ȱ�i�� ����insertģʽ ���ĺ�esc,:wq�˳�
## ׷������
```
echo world >> index.txt
```
> һ�����ںű�ʾ��ղ�д�룬�������ںű�ʾ׷������

## ������׷�ӵ��ݴ�����
```
git add . /git add -A �ļ���
```

## �ύ����ʷ����
```
git commit -m'ע��'
```

## �鿴�汾����־
```
git log --oneline
```

## �Ƚϲ�ͬ
- Ĭ�ϱȽϵ��ǹ��������ݴ���
```
git diff
```
- �������Ͱ汾��
```
git diff master
```
- �ݴ����Ͱ汾��
```
git diff --cached
```
## ��������ĳ���ļ����״��ύ
```
git add
git commit -m
git commit -a -m 'ע��'
```

## ���ر��ε�add����
```
git reset HEAD index.txt
```
## ���ݴ��������ݸ��ǵ�������
```
git checkout index.txt
```
> �ݴ�����û�л����ʷ��������

## �ع�
```
git reset --hard �汾��
```

## �鿴��ʷ�汾
```
git reflog
```

## �ع�ָ���ع������汾
```
git reset --hard HEAD^/HEAD~1 
```

## ��֧
- ������֧
```
git branch ��֧������
```
- �л���֧
```
git checkout dev
```
- �鿴���з�֧
```
git branch
```
- ɾ����֧
```
git branch -d dev
```
## �ȴ�����֧���н��뵽��֧
```
git branch dev
git checkout dev
git checkout -b dev
```
> git checkout -b gh-pages  һ����λ

## �ϲ���֧ �ڷ�֧�Ͻ��п���
- �������л�������֧�Ϻϲ����εĿ���
```
git merge 
```
> �������Ϻϲ��л�������֧��

## �����ͻ
��<<<<<  ======  >>>>>   ɾ��������Ҫ���ٴ�add commit ���ɺϲ���Ľű�
## �����ļ�
```
touch dev.js
```
- ��ʾͼ����ʾ��֧
```
git log --graph
```

```
git branch
git checkout
git merge
```

## ������ڿ���ʱ �л���֧ Ҫ��֤���������ݴ�����Ϊ�ɾ��ķ������л�

## ���浽��ʷ
- ����ʷ�������ݴ����͹�����
```
git stash
```
## �鿴���������
```
git stash list
```
## Ӧ����ʷ����ɾ����ʷ
```
git stash apply
git stash drop
=
git stash pop
```

## rebase ���
- rebase��merge������
- �����˺ϲ����� 
- ��������µ��ύ���ڵ����ύ�������֧�ϵ��ύ�����պϲ���һ���ύ
## cherry-pick ��ѡ��ѡ
