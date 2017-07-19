# Demo project created by Xiaozhong Hua (Jim)/
This is a demo project, especially working for mobile phone, which a http client/server session can run on a surface of cube.

## Includes
- touch.html provides the interfaces between user and server. To be beautiful, 5 images are displayed on the other surfaces of cube now :-) They can be replaced by video or other sessions.
- touch.css creates surfaces for cube.
- touch.js replies finger touching at mobile or mouse moving at computer, to rotate cube from one surface to another.
- sample.war, a Web ARchive file, can be put into $CATALINA_HOME/webapps, for examle, /usr/share/tomcat/webapps.

Then you can type: http://server_ip:8080/sample/media/cube-sessions/touch.html, to invoke the app.
- Hello.java, servelet demo called by touch.html, is at sample/WEB-INF/classes/mypackage.

## Setup & Run
- The demo has been verified with Apache Tomcat 7.0.68.
- Supposing tomcat's root directory is at /usr/share/tomcat, then the folder "cube-sessions" can be at /usr/share/tomcat/webapps/sample/media/cube-sessions.
- Open a browser and type: http://server_ip:8080/sample/media/cube-sessions/touch.html
- You shall see a page as [cube-sessions](screenshot-2017-07-19.png)
- Touch your smart phone to different direction, you could go to different surface on cube.
- On the surface [cube-sessions](screenshot-2017-07-19.png), as soon as you input words and press "Submit" button, the confirmation back from server will be displayed on the surface.

### Got reference from
- https://github.com/fofr/paulrhayes.com-experiments.
