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

卒業研究としてNoSQLデータベースに置けるスキーマ推薦を行っています。データベースにおけるスキーマはクエリやupdateの速度に直結するため、性能を追い求める際には非常に重要な項目となります。  

* keywords
    * Cassandra
    * HBase
    * <a class="text-link" href="https://github.com/michaelmior/NoSE">NoSE</a>

## Personal Interest {#personal}

NoSQLやRDBMSにおけるスキーマ・トランザクション・分散処理に関心があります。

## Career {#career}

* 2019年3/7-4/5の期間にサイバーエージェント秋葉原ラボにおいてインターンに参加しました。
   * 関連技術
        * Ruby
        * Java
        * HBase
        * openTSDB
        * docker
        * docker-compose
* 2018年8/13-9/7の期間にNTTの武蔵野研究所においてインターンに参加しました。
   * 関連技術
        * c++
        * Ruby
        * PostgreSQL
        * Ruby on Rails
* 2016年3月より、大学で使用する公費システム開発に携わっています。
    * 関連技術
        * C#
        * PostgreSQL
        * docker
        * docker-compose

## Licenses and Certifications {#licenses}

* 応用情報技術者
* TOEIC 845点
* 準中型免許(限定無し)

## Club Activity {#club}

* 人力飛行機制作研究会Albatross
    * 2017年度パイロット・プロジェクトリーダ・電装班長

## History {#history}

* 2018-04 ビックデータ工学講座 (鬼塚研) 正規配属
* 2017-04 ビックデータ工学講座 (鬼塚研) 配属
* 2015-04 大阪大学工学部電子情報工学科 入学
* 2015-03 清教学園高等学校 卒業

## Hobby {#hobby}

* サイクリング
* ギター(少々)
