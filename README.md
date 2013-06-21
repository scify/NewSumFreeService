NewSumFreeService
=
[NewSum](http://www.scify.gr/site/en/our-projects/completed-projects/newsum-menu-en) is a cutting edge summarization application developed for getting summaries from various news sources.
-
NewSum requires java 6 and above.


NewSumFreeService is responsible for fetching data from the server to the clients. 

The repository is set up for easy integration with the Netbeans IDE. It requires NetBeans and glassfish server. The domain where the service will be deployed needs to have awareness of all the information stored by NewSumServer, therefore in your domains root folder, a soft link called 'data' pointing to NewSumServer/data folder should be created.

[SciFY NPC](http://www.scify.org), 2013
-

The project depends on the following libraries

- NewSumServer.jar
- [JInsect.jar](http://sourceforge.net/projects/jinsect/)
- [Jama-1.0.2.jar](http://math.nist.gov/javanumerics/jama/)
- OpenJGraph.jar
- [RSSParser.jar](http://commons.apache.org/dormant/feedparser/source-repository.html)
- [gson-2.2.4.jar](http://code.google.com/p/google-gson/)
- [jaxen-1.1.3.jar](http://jaxen.codehaus.org/)
- [jdom-1.1.3.jar](http://www.jdom.org/index.html)
- [jsoup-1.6.2.jar](http://jsoup.org/)
- [jwnl-1.3.3.jar](http://sourceforge.net/projects/jwordnet/)
- [log4j-1.2.16.jar](http://logging.apache.org/log4j/1.2/)
- [lucene-analyzers-3.6.1.jar](http://lucene.apache.org/core/)
- [lucene-core-3.6.1.jar](http://lucene.apache.org/core/)
- opennlp-maxent-3.0.2-incubating.jar
- [opennlp-tools-1.5.2-incubating.jar](http://opennlp.apache.org/index.html)
- opennlp-uima-1.5.2-incubating.jar 
- [weka.jar](http://sourceforge.net/projects/weka/)


Contributors
-
- *George G. <ggianna@scify.org>*
- *George K. <gkiom@scify.org>*
