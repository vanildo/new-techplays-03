oc new-app --name=simple-stuff https://github.com/vanildo/new-techplays-03.git --as-deployment-config

oc create route edge --service=simple-stuff

route.route.openshift.io/simple-stuff created

curl -k https://simple-stuff-vanildov-br.sol-arc-bootcamp-162151-f72ef11f3ab089a8c677044eb28292cd-0000.us-east.containers.appdomain.cloud/simple-stuff/simple/simon

