sbt-simple-junit-xml-reporter-plugin
====================================

A pretty basic plugin for sbt to output junit xml reports from tests.

To use add:
   
	lazy val root = project.in( file(".") ).dependsOn( junitXmlReportPlugin )
	lazy val junitXmlReportPlugin = uri("git://github.com/bseibel/sbt-simple-junit-xml-reporter-plugin.git")


to project/project/plugins.scala
