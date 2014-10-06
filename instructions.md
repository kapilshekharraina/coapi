Get started with coapi
-----------------------------------
Welcome to Java Web Starter application!

This sample application demonstrates how to write a Java Web application (powered by WebSphere Liberty) and deploy it on Bluemix.

1. [Install the cf command-line tool](https://www.ng.bluemix.net/docs/#starters/BuildingWeb.html#install_cf).
2. [Download the starter application package](https://ace.ng.bluemix.net:443/rest/../rest/apps/62447c76-a379-4b59-82b5-3253f6a1849d/starter-download).
3. Extract the package and `cd` to it.
4. Connect to Bluemix:

		cf api https://api.ng.bluemix.net

5. Log into Bluemix:

		cf login -u kapil.shekhar.raina@accenture.com
		cf target -o kapil.shekhar.raina@accenture.com -s dev
				
6. Compile the Java code and generate the war package using ant.
7. Deploy your app:

		cf push coapi -p webStarterApp.war

8. Access your app: [http://coapi.mybluemix.net](http://coapi.mybluemix.net)
