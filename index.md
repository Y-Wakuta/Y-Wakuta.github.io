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

大阪大学工学部電子情報工学科情報通信工学科目  
<a class="text-link" href="http://www-bigdata.ist.osaka-u.ac.jp/ja/home/">鬼塚研究室</a>  
涌田 悠佑 (yusuke wakuta)  
email:  wakuta.yusuke [at] ist.osaka-u.ac.jp

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
            {% endif %} {% if site.hatena %}
            <a type="button" href="https://yusuke-haimenhikou.hatenablog.com">
                <img src="hatenablog-logo.jpg" width="23"  height="23">
            </a>
            {% endif %}
        </ul>

## Research Interest {#research}

卒業研究としてNoSQLデータベースに置けるスキーマ推薦を行っています。データベースにおけるスキーマはクエリやupdateの速度に直結するため、性能を追い求める際には非常に重要な項目となります。  

* keywords
    * Cassandra
    * HBase
    * [NoSE](https://github.com/michaelmior/NoSE)

## Personal Interest {#personal}

NoSQLやRDBMSにおけるスキーマ・トランザクション・分散処理に関心があります。

## Career {#career}

* 2016年3月より、大学で使用する公費システム開発に携わっています。
    * 関連技術
        * C#
        * PostgreSQL
        * docker
        * docker-compose
* 2018年8/13-9/7にNTTの武蔵野研究所においてインターンに参加しました。
   * 関連技術
        * c++
        * Ruby
        * PostgreSQL
        * Ruby on Rails

## History {#history}

* 2018-04 ビックデータ工学講座 (鬼塚研) 正規配属
* 2017-04 ビックデータ工学講座 (鬼塚研) 配属
* 2015-04 大阪大学工学部電子情報工学科 入学
* 2015-03 清教学園 卒業

## Club Activity {#club}

* 人力飛行機制作研究会Albatross
    * 2017年度パイロット・プロジェクトリーダ・電装班長

## Hobby {#hobby}

* サイクリング
* ギター(少々)