<H1> Notes </H1>
<p>-	Listened to the podcast and did the readings. </p>
<p>-	Did the short Excel intro </p>
<h3> Voyant </h3> 
<p>-	Started working with Voyant tools. The first time I tried to run it according to the instructions I got this error. </p>

```
craftingdh.netlify.app
java.net.UnknownHostException: craftingdh.netlify.app
	at java.net.AbstractPlainSocketImpl.connect(AbstractPlainSocketImpl.java:184)
	at java.net.SocksSocketImpl.connect(SocksSocketImpl.java:392)
	at java.net.Socket.connect(Socket.java:589)
	at sun.security.ssl.SSLSocketImpl.connect(SSLSocketImpl.java:673)
	at sun.net.NetworkClient.doConnect(NetworkClient.java:175)
	at sun.net.www.http.HttpClient.openServer(HttpClient.java:463)
	at sun.net.www.http.HttpClient.openServer(HttpClient.java:558)
	at sun.net.www.protocol.https.HttpsClient.(HttpsClient.java:264)
	at sun.net.www.protocol.https.HttpsClient.New(HttpsClient.java:367)
	at sun.net.www.protocol.https.AbstractDelegateHttpsURLConnection.getNewHttpClient(AbstractDelegateHttpsURLConnection.java:191)
	at sun.net.www.protocol.http.HttpURLConnection.plainConnect0(HttpURLConnection.java:1156)
	at sun.net.www.protocol.http.HttpURLConnection.plainConnect(HttpURLConnection.java:1050)
	at sun.net.www.protocol.https.AbstractDelegateHttpsURLConnection.connect(AbstractDelegateHttpsURLConnection.java:177)
	at sun.net.www.protocol.http.HttpURLConnection.getInputStream0(HttpURLConnection.java:1564)
	at sun.net.www.protocol.http.HttpURLConnection.getInputStream(HttpURLConnection.java:1492)
	at sun.net.www.protocol.https.HttpsURLConnectionImpl.getInputStream(HttpsURLConnectionImpl.java:263)
	at org.voyanttools.trombone.input.source.UriInputSource.getInputStream(UriInputSource.java:144)
	at org.voyanttools.trombone.storage.file.FileStoredDocumentSourceStorage.getStoredDocumentSource(FileStoredDocumentSourceStorage.java:115)
	at org.voyanttools.trombone.tool.build.DocumentStorer.run(DocumentStorer.java:77)
	at org.voyanttools.trombone.tool.build.DocumentStorer.run(DocumentStorer.java:63)
	at org.voyanttools.trombone.tool.build.RealCorpusCreator.run(RealCorpusCreator.java:71)
	at org.voyanttools.trombone.tool.build.RealCorpusCreator.run(RealCorpusCreator.java:57)
	at org.voyanttools.trombone.tool.corpus.CorpusManager.run(CorpusManager.java:104)
	at org.voyanttools.trombone.tool.corpus.CorpusManager.getCorpus(CorpusManager.java:112)
	at org.voyanttools.trombone.tool.corpus.AbstractCorpusTool.run(AbstractCorpusTool.java:57)
	at org.voyanttools.trombone.tool.util.ToolRunner.run(ToolRunner.java:134)
	at org.voyanttools.trombone.Controller.run(Controller.java:110)
	at org.voyanttools.voyant.Trombone.runTromboneController(Trombone.java:337)
	at org.voyanttools.voyant.Trombone.doRequest(Trombone.java:311)
	at org.voyanttools.voyant.Trombone.doRequest(Trombone.java:146)
	at org.voyanttools.voyant.Trombone.doPost(Trombone.java:87)
	at javax.servlet.http.HttpServlet.service(HttpServlet.java:650)
	at javax.servlet.http.HttpServlet.service(HttpServlet.java:731)
	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:303)
	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:208)
	at org.apache.tomcat.websocket.server.WsFilter.doFilter(WsFilter.java:52)
	at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:241)
	at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:208)
	at org.apache.catalina.core.StandardWrapperValve.invoke(StandardWrapperValve.java:218)
	at org.apache.catalina.core.StandardContextValve.invoke(StandardContextValve.java:110)
	at org.apache.catalina.authenticator.AuthenticatorBase.invoke(AuthenticatorBase.java:506)
	at org.apache.catalina.core.StandardHostValve.invoke(StandardHostValve.java:169)
	at org.apache.catalina.valves.ErrorReportValve.invoke(ErrorReportValve.java:103)
	at org.apache.catalina.valves.RemoteIpValve.invoke(RemoteIpValve.java:683)
	at org.apache.catalina.valves.AccessLogValve.invoke(AccessLogValve.java:962)
	at org.apache.catalina.core.StandardEngineValve.invoke(StandardEngineValve.java:116)
	at org.apache.catalina.connector.CoyoteAdapter.service(CoyoteAdapter.java:445)
	at org.apache.coyote.http11.AbstractHttp11Processor.process(AbstractHttp11Processor.java:1087)
	at org.apache.coyote.AbstractProtocol$AbstractConnectionHandler.process(AbstractProtocol.java:637)
	at org.apache.tomcat.util.net.JIoEndpoint$SocketProcessor.run(JIoEndpoint.java:316)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at org.apache.tomcat.util.threads.TaskThread$WrappingRunnable.run(TaskThread.java:61)
	at java.lang.Thread.run(Thread.java:748)
  
 ```
<p> - After looking for solutions on the discord I saw some others experiencing the same issue. It seems like the problem is server side, which makes sense since it is a java error. I shall download the server myself and run it on my machine, hopefully that fixes the problem. </p> 
<p> - After a long download I finally got Voyant Server working on my machine. </p>
<p> - My initial corpus id was: 49f48aa297f23faaecb77e664a9f0650 </p> 
