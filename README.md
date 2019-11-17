Bucket Name:- bucket-shwetali-apisero
Topic Name:- Mule-SNS

Log
13:11:13.432     11/17/2019     Deployment     system     SYSTEM
Application queued to be deployed...
13:11:13.630     11/17/2019     Deployment     system     SYSTEM
Deploying application to 1 workers in us-east-2 region(s).
13:11:14.586     11/17/2019     Deployment     system     SYSTEM
Provisioning CloudHub worker in region=us-east-2...
13:11:15.139     11/17/2019     Deployment     system     SYSTEM
Starting CloudHub worker at 3.133.122.51 ...
13:11:31.004     11/17/2019     Deployment     system     SYSTEM
Worker(3.133.122.51): Starting your application on mule=4.2.1...
13:11:33.651     11/17/2019     Worker-0     qtp1788495079-37     INFO
The PersistentQueueManager is NOT configured. The normal VM queue manager will be used.
13:11:40.680     11/17/2019     Worker-0     qtp1788495079-37     INFO
Loaded MuleMessageBuilderFactory implementation 'org.mule.runtime.core.internal.message.DefaultMessageBuilderFactory' from classloader 'org.mule.runtime.module.reboot.internal.MuleContainerSystemClassLoader@423a8004'
13:11:40.701     11/17/2019     Worker-0     qtp1788495079-37     INFO
Loaded BindingContextBuilderFactory implementation 'org.mule.runtime.core.api.el.DefaultBindingContextBuilderFactory' from classloader 'org.mule.runtime.module.reboot.internal.MuleContainerSystemClassLoader@423a8004'
13:11:41.934     11/17/2019     Worker-0     qtp1788495079-37     INFO
Using files for tx logs /opt/mule/mule-4.2.1/./.mule/research/queue-tx-log/tx1.log and /opt/mule/mule-4.2.1/./.mule/research/queue-tx-log/tx2.log
13:11:41.952     11/17/2019     Worker-0     qtp1788495079-37     INFO
Using files for tx logs /opt/mule/mule-4.2.1/./.mule/research/queue-xa-tx-log/tx1.log and /opt/mule/mule-4.2.1/./.mule/research/queue-xa-tx-log/tx2.log
13:11:42.015     11/17/2019     Worker-0     qtp1788495079-37     INFO
Initialising Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-Amazon_S3_Configuration
13:11:42.132     11/17/2019     Worker-0     qtp1788495079-37     INFO
Initialising Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Listener_config
13:11:42.570     11/17/2019     Worker-0     qtp1788495079-37     INFO
Initialising flow: researchFlow
13:11:42.699     11/17/2019     Worker-0     qtp1788495079-37     INFO
Initialising Bean: listener
13:11:43.291     11/17/2019     Worker-0     qtp1788495079-37     INFO
Persistent queues is not enabled for batch module as it was not configured in Cloudhub console
13:11:43.341     11/17/2019     Worker-0     qtp1788495079-37     INFO
Starting ResourceManager
13:11:43.341     11/17/2019     Worker-0     qtp1788495079-37     INFO
Started ResourceManager
13:11:43.348     11/17/2019     Worker-0     qtp1788495079-37     INFO
Starting Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-Amazon_S3_Configuration
13:11:43.963     11/17/2019     Worker-0     qtp1788495079-37     INFO
Starting Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Listener_config
13:11:43.988     11/17/2019     Worker-0     qtp1788495079-37     INFO
Starting flow: researchFlow
13:11:44.212     11/17/2019     Worker-0     qtp1788495079-37     INFO
Starting Bean: listener
13:11:44.224     11/17/2019     Worker-0     qtp1788495079-37     INFO

**********************************************************************
* Application: research                                              *
* OS encoding: UTF-8, Mule encoding: UTF-8                           *
*                                                                    *
**********************************************************************
13:11:44.521     11/17/2019     Deployment     system     SYSTEM
Worker(3.133.122.51): Your application has started successfully.
13:11:44.913     11/17/2019     Deployment     system     SYSTEM
