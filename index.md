---
layout: default 
---

<header class="bloghead">
    <nav class="bloghead-nav">
        {% for nav in site.nav %}
        <a class="text-link" href="{{ nav.href }}">{{ nav.name }}<span> &nbsp;/&nbsp; </span></a> {% endfor %}
    </nav>
</header>

## About Me {#aboutme}

情報科学研究科博士前期課程マルチメディア工学専攻
<a class="text-link" href="http://www-bigdata.ist.osaka-u.ac.jp/ja/home/">鬼塚研究室</a>  
涌田 悠佑 (yusuke wakuta)  
<a class="text-link" href="https://yusuke-haimenhikou.hatenablog.com">はてな</a>  
Email:  wakuta.yusuke [at] ist.osaka-u.ac.jp  
<ul class="social">
            {% if site.github %}
            <a type="button" href="http://github.com/{{ site.github }}">
                <i class="fa fa-github"></i>
            </a>
            {% endif %} {% if site.twitter %}
            <a type="button" href="http://twitter.com/{{ site.twitter }}">
                <i class="fa fa-twitter"></i>
            </a>
            {% endif %} {% if site.linkedin %}
            <a type="button" href="http://linkedin.com/in/{{ site.linkedin }}">
                <i class="fa fa-linkedin"></i>
            </a>
            {% endif %}
        </ul>

## Research Interest {#research}

NoSQL データベースに置けるスキーマ推薦技術に関する研究を行っています。データベースにおけるスキーマはクエリ・更新処理の速度に直結するため、性能を追い求める際には非常に重要な項目となります。

* keywords
    * Cassandra 
    * HBase 
    * <a class="text-link" href="https://github.com/michaelmior/NoSE">NoSE</a>

## Publications {#publications}

* Secondary index を活用する NoSQL スキーマ推薦によるクエリ処理高速化
  <ol>
     <li><span style="color: #808080; background-color: transparent">涌田 悠佑, 善明 晃由, 松本 拓海, 佐々木 勇和, 鬼塚 真</span></li> 
     <li><span style="color: #808080; background-color: transparent">The 3rd cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming (xSIG2019) (2019.05)</span></li> 
  </ol>
* Secondary index を活用する NoSQL スキーマ推薦による Query 処理高速化
  <ol>
     <li><span style="color: #808080; background-color: transparent">涌田 悠佑, 善明 晃由, 松本 拓海, 佐々木 勇和, 鬼塚 真</span></li> 
     <li><span style="color: #808080; background-color: transparent">データ工学と情報マネジメントに関するフォーラム (DEIM2019) (2019.03)   </span></li> 
  </ol>

## Awards {#awards}

* Outstanding Significance Award (xSIG2019)
* 優秀インタラクティブ賞 (DEIM2019)
* 学生プレゼンテーション賞 (DEIM2019)
* 阪大情報科学研究科院試は専攻内首席でした。(ここ以外書く機会も無いので記載)

## Personal Interest {#personal}

NoSQL や RDBMS におけるスキーマ・トランザクション・分散処理に関心があります。

## Experience {#experience}

* 2016年3月より、大学で使用する公費システム開発に携わっています。
    * 関連技術
        * C#
        * PostgreSQL
        * docker
        * docker-compose
* 2018年8/13-9/7の期間にNTTの武蔵野研究所においてインターンに参加しました。
   * 関連技術
        * c++
        * Ruby
        * PostgreSQL
        * Ruby on Rails
* 2019年3/7-4/5の期間にサイバーエージェント秋葉原ラボにおいてインターンに参加しました。
   * 関連技術
        * Ruby
        * Java
        * HBase
        * openTSDB
        * docker
        * docker-compose
* 2019年5/16 よりサイバーエージェントで長期インターンとして再度雇用頂き、大阪オフィスより秋葉原ラボの業務に携わらせて頂いています。
* 2019年9/16-11/15の期間にアメリカのロチェスター工科大学においてインターンに参加しました。
* 2019年12/2-12/13の期間に M3 においてインターンに参加しました。

## Education {#education}

* 2015-03 清教学園高等学校 卒業
* 2015-04 大阪大学工学部電子情報工学科 入学
* 2017-04 ビックデータ工学講座 (鬼塚研) 早期配属
* 2018-04 ビックデータ工学講座 (鬼塚研) 正規配属
* 2019-04 大阪大学情報科学研究科マルチメディア専攻ビッグデータ工学講座 (鬼塚研) 配属 

## Licenses and Certifications {#licenses}

* 応用情報技術者
* TOEIC 845点
* 準中型免許(限定無し)

## Club Activity {#club}

* <a class="text-link" href="http://albatross-osaka.net/">大阪大学飛行機制作研究会albatross</a>  
    * 2017年度パイロット・プロジェクトリーダ・電装班長

## Hobby {#hobby}

* サイクリング
* トラック運転
