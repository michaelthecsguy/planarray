Google App Engine First Attempt with Native Java, JSTL, JSP
=============================

This is a generated application from the appengine-skeleton archetype.

$mvn clean install

--for hot re-deploy locally--
$mvn clean appengine:devserver

--for upload to Google App Engine Cloud--
--go to appengine.xml from default target folder to change the attribute value from auto to manual
--then,
$mvn appengine:update
