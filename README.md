# gitbook ��������

**��װ Node.js �� npm**

[https://nodejs.org/en/download/](https://nodejs.org/en/download/)

**��װ GitBook �����й���**

```bash
npm install gitbook-cli -g
```

**������Ŀ**

```bash
git clone xxx_project
```

**���� GitBook**

***��ʼ����Ŀ(��ѡ)***

```bash
gitbook init xxx_project
```

������Ŀ��

```bash
cd xxx_project
```

��ʼ��GitBook���Զ���

```bash
vim book.json
```

������Ŀ��ִ�й�����

```bash
rm -rf docs && gitbook build . docs
```