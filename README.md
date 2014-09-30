<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>WebSphere MQ Monitoring Fastpack</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>WebSphere MQ Monitoring Fastpack</h1>
    <div class="section-2"  id="27623632_WebSphereMQMonitoringFastpack-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/25789254/logo_wssoftware.gif" alt="images_community/download/attachments/25789254/logo_wssoftware.gif" class="confluence-embedded-image image-left" />
            </p>
    <p>
The dynaTrace FastPack for WebSphere MQ enables easy out-of-the-box monitoring of WebSphere MQ Queues, Topics and Subscriptions. The FastPack consists of a custom Monitor, Sample Profile and Dashboards.    </p>
    </div>
    <div class="section-2"  id="27623632_WebSphereMQMonitoringFastpack-FastPackDetails"  >
        <h2>Fast Pack Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">WebSphere MQ Monitoring FastPack</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1.0.3    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
3.2, 3.5, 4.1    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
dynaTrace software    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Community Supported </a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FastPack Contents    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_27688973_3_WebSphereFastpackDashboardsAndProfile.zip">System Profile and Dashboards </a><br/><a href="attachments_77660172_1_com.dynatrace.plugins.mq_2.0.0.jar">WebSphere MQ Monitoring Plugin</a> (<a href="https://community/display/DL/WebSphere+MQ+Monitoring+Plugin">Plugin Page</a>)    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="27623632_WebSphereMQMonitoringFastpack-WebSphereMQQueueDashboard"  >
        <h2>WebSphere MQ Queue Dashboard</h2>
    <p>
            <img src="images_community/download/attachments/27623632/Queue_Dashboard.png" alt="images_community/download/attachments/27623632/Queue_Dashboard.png" class="" />
            </p>
    <p>
The WebSphere MQ Queue Dashboard enables you to easily monitor a a Queue and its Queue Manager. It shows you    </p>
<ul class=" "><li class=" ">    <p>
Whether the QueueManager is running    </p>
</li><li class=" ">    <p>
How much time passed by since the last enqueue and dequeue    </p>
</li><li class=" ">    <p>
How many processes are currently reading from or writing to the queue    </p>
</li><li class=" ">    <p>
How many messages there currently are on the queue    </p>
</li><li class=" ">    <p>
How old the oldest message is giving you<br/>This gives you an idea if messages stay on the queue longer than should be.    </p>
</li></ul>    <p>
In addition it contains traffic lights for all major metrics, which when you define your thresholds enable you too see the health state of your queue at one single glance    </p>
    </div>
    <div class="section-2"  id="27623632_WebSphereMQMonitoringFastpack-WebSphereMQTopicDashboard"  >
        <h2>WebSphere MQ Topic Dashboard</h2>
    <p>
            <img src="images_community/download/attachments/27623632/Topic_Dashboard.png" alt="images_community/download/attachments/27623632/Topic_Dashboard.png" class="" />
            </p>
    <p>
The WebSphere MQ Topic Dashboard enables you to easily monitor Topic and its Queue Manager. It shows you    </p>
<ul class=" "><li class=" ">    <p>
Whether the QueueManager is running    </p>
</li><li class=" ">    <p>
The active Publisher and Subscriber count    </p>
</li></ul>    <p>
In addition it contains traffic lights for all major metrics, which when you define your thresholds enable you too see the health state of your queue at one single glance    </p>
    </div>
    <div class="section-2"  id="27623632_WebSphereMQMonitoringFastpack-WebSphereMQMonitor"  >
        <h2>WebSphere MQ Monitor</h2>
    <p>
The Monitor uses the local WebSphere MQ installation of the running collector to gather its metrics. This means that at least the MQ client needs to be installed on the machine that is running the dynaTrace Collector<br/>It allows to monitor all major MQ types: Queue, Topic, Subscription.    </p>
    <p>
            <img src="images_community/download/attachments/27623522/MQ_Settings_Dialog.png" alt="images_community/download/attachments/27623522/MQ_Settings_Dialog.png" class="" />
            </p>
    <p>
The only thing to configure are the    </p>
<ul class=" "><li class=" ">    <p>
Binary Installation directory of the WebSphere MQ client/server installation    </p>
</li><li class=" ">    <p>
Queue manager name    </p>
</li><li class=" ">    <p>
queue/topic/subscription name    </p>
</li></ul>    <p>
For more information please see the <a href="https://community/display/DL/WebSphere+MQ+Monitoring+Plugin">WebSphere MQ Monitoring plugin</a> page.    </p>
    </div>
    <div class="section-2"  id="27623632_WebSphereMQMonitoringFastpack-FastPackInformation"  >
        <h2>FastPack Information</h2>
    <p>
The WebSphere MQ Monitoring FastPack contains everything to get started with WebSphere MQ monitoring.    </p>
<ul class=" "><li class=" ">    <p>
A system profile with preconfigured schedules for monitoring the demo queue (<i class=" ">postcard</i>).    </p>
</li><li class=" ">    <p>
A WebSphere MQ Queue Dashboard for monitoring the Queue manager and a queue.    </p>
</li><li class=" ">    <p>
A WebSphere MQ Topic Dashboard for monitoring the Publishers and Subscribers of a topic    </p>
</li></ul>    </div>
    <div class="section-2"  id="27623632_WebSphereMQMonitoringFastpack-Installation"  >
        <h2>Installation</h2>
<ol class=" "><li class=" ">    <p>
Download and import the Dashboards and the System Profile on your dynaTrace Server    </p>
</li><li class=" ">    <p>
Download and import the Monitor Plugin to your dynaTrace Server    </p>
</li></ol>    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>