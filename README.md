# solr-setup
1. clone and copy this folder to your tomcat webapps folder, like C:\Program Files\apache-tomcat-8.5.15\webapps
2. clone solr home repo and put to a dir like D:
3. modify the web.xml in solr WEB-INF folder to change the solr home dir:
    <env-entry>
       <env-entry-name>solr/home</env-entry-name>
       <env-entry-value>d:/solr_home/solr</env-entry-value>
       <env-entry-type>java.lang.String</env-entry-type>
    </env-entry>
