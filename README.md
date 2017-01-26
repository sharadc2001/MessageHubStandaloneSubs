<h1>MessageHubStandaloneSubs</h1><br/>
<h2>Description: The code is used to test data receiving from message hub topic in a standalone mode through eclipse</h2><br/>
1. Change the <b>apiKey</b> and <b>kafkaHost (kafkaHostUS,kafkaHostEU)</b> and <b>topic</b> variables in the code (point to EU or US South).<br/>
2. Add approriate <b>username</b> and <b>password</b> in jaas.conf and jaas.conf.template<br/>
3. Run <b>MessageHubJavaSample</b> class to get the messages <br/>

In eclipse Run configuration of the class give :<br/>

<h3>VM Arguments</h3><br/>
-Djava.security.properties=resources/jaas.conf

<h3>Program Arguments</h3><br/>
Any three dummy values seperated by space
