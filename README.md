## Groovy script to cleanup Jenkins workspaces ##

This system script will walk through all jobs, starting with a certain prefix, and delete their workspaces from all connected nodes.

This is very useful when you have a multi-job project that you want to clean up at once. Usually you run system Groovy scripts from jenkins script console, but if you want a more convenient way, try out the [Scriptler Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Scriptler+Plugin). It allows you to run system scripts in a manner similar to regular jobs.

### Usage ###

Specify the ```JOB_PREFIX``` variable and paste the script to the script console. With [Scriptler](https://wiki.jenkins-ci.org/display/JENKINS/Scriptler+Plugin) you can make this variable a job argument.

### License ###

The script is MIT-licensed, so you are free to use it in your commercial setting.
