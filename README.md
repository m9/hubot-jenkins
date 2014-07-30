#Description:
 Interact with your Jenkins CI server

#Dependencies:
 None

#Configuration:
* HUBOT_JENKINS_URL
* HUBOT_JENKINS_AUTH

Auth should be in the `user:password` format.

#Commands:
* hubot jenkins b <jobNumber>` - builds the job specified by jobNumber. List jobs to get number.
* hubot jenkins build <job>` - builds the specified Jenkins job
* hubot jenkins build <job>, <params>` - builds the specified Jenkins job with parameters as key=value&key2=value2
* hubot jenkins list <filter>` - lists Jenkins jobs
* hubot jenkins describe <job>` - Describes the specified Jenkins job
* hubot jenkins last <job>` - Details about the last build for the specified Jenkins job