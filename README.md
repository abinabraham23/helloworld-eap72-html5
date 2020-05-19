# helloworld-eap72-html5
The helloworld-html5 quickstart demonstrates the use of CDI 1.2 and JAX-RS 2.0 in JBoss Enterprise Application Platform Server 7.2 or later using the HTML5 + REST architecture.

The application is basically a smart, HTML5, CSS3, and JavaScript front-end using RESTful services on the backend.
1. HelloWorld.java: Establishes the RESTful endpoints using JAX-RS.
2. web.xml: Maps RESTful endpoints to /hello.
3. index.html: Is a jQuery augmented plain old HTML5 web page.

## Access the Application

The application will be running at the following URL http://<hostname>:8080/helloworld-html5/

### Test the XML Content

We can test The XML content by sending an HTTP POST to the following URL: http://<hostname>:8080/helloworld-html5/hello/xml/YOUR_NAME

Type the following cURL command in terminal to issue the POST command:
> curl -i -X POST http://<hostname>:8080/${project.artifactId}/hello/xml/__YOUR_NAME__

### Test the JSON Content

We can test the JSON content by sending an HTTP POST to the following URL: http://<hostname>:8080/helloworld-html5/hello/json/YOUR_NAME

Type the following cURL command in terminal to issue the POST command:
> curl -i -X POST http://<hostname>:8080/${project.artifactId}/hello/json/YOUR_NAME

19-05-2020 -- Added a small change to test the github webhook feature once again..