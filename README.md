#我的Maven quickstart模板
##步骤
<pre>
1.mvn archetype:create-from-project
2.cd target\generated-sources\archetype
3.mvn install 
4.mvn archetype:crawl
5.然后在mvn_repo根目录下的archetype-catalog.xml中会生成对应的archetype节点
6.New maven时，在右侧Create from archetype中点击Add archetype，并输入archetype-catalog.xml中对应的属性值
7.点击新增的archetype即可
</pre>