# OpenShift WordPress standalone 

OpenShift WordPress standalone template with sensible settings changed in Dockerfile

* Create & install template:

  ``
  oc process -f wordpress-standalone.yml | oc apply -f - 
  ``
