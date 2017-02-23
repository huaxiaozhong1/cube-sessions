# Demo project created by Xiaozhong Hua (Jim)/
This is a demo project, especially working for mobile phone, which a http client/server session can run on a surface of cube.

## Includes
- touch.html provides the interfaces between user and server. To be beautiful, 5 images are displayed on the other surfaces of cube now :-) They can be replaced by video or other sessions.
- touch.css creates surfaces for cube. 
- touch.js replies finger touching at mobile or mouse moving at computer, to rotate cube from one surface to another.
- sample.war, a Web ARchive file, can be put into $CATALINA_HOME/webapps, for examle, /usr/share/tomcat/webapps. Then you can type: http://server_ip:8080/sample/media/cube-sessions/touch.html, to invoke the app.
- Hello.java, servelet demo called by touch.html, is at sample/WEB-INF/classes/mypackage.

### Got reference from
- https://github.com/fofr/paulrhayes.com-experiments. 
