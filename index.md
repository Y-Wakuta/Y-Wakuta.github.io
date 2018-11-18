---
layout: default 
---
<header class="bloghead">
    <h1 class="bloghead-title">
    <a href="{{ site.url }}/">Overview</a>
  </h1>
    <nav class="bloghead-nav">
        {% for nav in site.nav %}
        <a class="head-link" href="{{ nav.href }}">{{ nav.name }}<span> &nbsp;/&nbsp; </span></a> {% endfor %}
    </nav>
</header>

## About Me

大阪大学工学部電子情報工学科情報通信工学科目  
<a class="text-link" href="http://www-bigdata.ist.osaka-u.ac.jp/ja/home/">鬼塚研究室</a>  
涌田 悠佑 (yusuke wakuta)  

## Research Interest

卒業研究としてNoSQLデータベースに置けるスキーマ推薦を行っています。データベースにおけるスキーマはクエリやupdateの速度に直結するため、性能を追い求める際には非常に重要な項目となります。

## Personal Interest

NoSQLやRDBMSにおけるスキーマ・トランザクション・分散処理に興味があります。

## Career

* 2016年3月より、大学で使用する公費システム開発に携わっています。関連技術: C#, PostgreSQL, docker, docker-compose
* 2018年8/13-9/7にNTTの武蔵野研究所においてインターンに参加しました。
    * hoge 
