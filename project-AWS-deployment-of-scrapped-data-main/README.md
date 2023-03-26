For deployment on web services portal , our code first needs to be pushed on to github .

we would be using two services of web portal namely :

 * Codepipeline
 * Elastic Bandstalk

our code will first go to github and from there it would be used to create a codepipline and at the same time
app name would also be used for creating a codepipline. The app name we would be getting after initializing a Elastic bandstalk which in turn will 
create an application for us . 
this appilcation would be required to create a codepipline in order to successfully deploy our project.
