# サッカー情報管理システム
## プロジェクトの概要
このシステムでは、
以下の内容を管理します。<br>
このシステムでは、<br>以下の内容を管理します。

- チームリスト
    1. Jリーグ
    1. 番号は振らない方が便利
    1. 欧州リーグ
- 選手リスト
- 試合結果

## ページ構成
| URL | 内容 | サーブレット | HTMLファイル |
|:-----:|:-----:|:-----------:|:-------------|
|/home|ホーム|HomeServlet|index.jsp|
|/list| チーム紹介| TeamServlet|list.jsp|


### domainクラスの例
```java
public class Team{
    private Integer id;
    private String name;
}

```
|   aaa |    bbb     |   ccc | ddd    |
| ----: | :--------: | ----: | :----- |
|  hoge |   日本語   |       |        |
| aiueo | kakikukeko | sashi | suseso |
|    ta |     ti     |    tu | to     |
|       |            |       |        |
