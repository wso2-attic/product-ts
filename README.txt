================================================================================
                        WSO2 Task Server 1.1.0
================================================================================

Welcome to the WSO2 TS 1.1.0 release

WSO2 TS is a server that can be used to define web tasks. That can be scheduled
by users to trigger remote tasks.

This is based on the revolutionary WSO2 Carbon [Middleware a' la carte]
framework. All the major features have been developed as pluggable Carbon
components.

Key Features of WSO2 TS
==================================

1. Scheduling remote web tasks.
2. Interfacing Carbon server with Task Server as the task provider.

Installation & Running
==================================

1. Extract the wso2ts-1.1.0.zip and go to the extracted directory
2. Run the wso2server.sh or wso2server.bat as appropriate
3. Point your favourite browser to

    https://localhost:9443/carbon

4. Use the following username and password to login

    username : admin
    password : admin

WSO2 TS 1.1.0 distribution directory structure
=============================================

	CARBON_HOME
		|- bin <folder>
		|- dbscripts <folder>
		|- lib <folder>
		|- repository <folder>
			|-- logs <folder>
			|--- database <folder>
		|--- conf <folder>
		|- resources <folder>
		|- tmp <folder>
		|- LICENSE.txt <file>
		|- README.txt <file>
		|- INSTALL.txt <file>

    - bin
	  Contains various scripts .sh & .bat scripts

	- conf
	  Contains configuration files

	- database
      Contains the database

    - dbscripts
      Contains all the database scripts

    - lib
	  Contains the basic set of libraries required to startup TS
	  in standalone mode

	- repository
	  The repository where services and modules deployed in WSO2 TS
	  are stored. In addition to this the components directory inside the
	  repository directory contains the carbon runtime and the user added
	  jar files including mediators third party libraries and so on..

	- logs
	  Contains all log files created during execution

	- resources
	  Contains additional resources that may be required, including sample
	  configuration and sample resources

	- tmp
	  Used for storing temporary files, and is pointed to by the
	  java.io.tmpdir System property

	- LICENSE.txt
	  Apache License 2.0 and the relevant other licenses under which
	  WSO2 TS is distributed.

	- README.txt
	  This document.

    - INSTALL.txt
      This document will contain information on installing WSO2 TS


Support
==================================

WSO2 Inc. offers a variety of development and production support
programs, ranging from Web-based support up through normal business
hours, to premium 24x7 phone support.

For additional support information please refer to http://wso2.com/support/

For more information on WSO2 TS, visit the WSO2 Oxygen Tank (http://wso2.org)

Issue Tracker
==================================

  https://wso2.org/jira/browse/CARBON
  https://wso2.org/jira/browse/TS

Crypto Notice
==================================

   This distribution includes cryptographic software.  The country in
   which you currently reside may have restrictions on the import,
   possession, use, and/or re-export to another country, of
   encryption software.  BEFORE using any encryption software, please
   check your country's laws, regulations and policies concerning the
   import, possession, or use, and re-export of encryption software, to
   see if this is permitted.  See <http://www.wassenaar.org/> for more
   information.

   The U.S. Government Department of Commerce, Bureau of Industry and
   Security (BIS), has classified this software as Export Commodity
   Control Number (ECCN) 5D002.C.1, which includes information security
   software using or performing cryptographic functions with asymmetric
   algorithms.  The form and manner of this Apache Software Foundation
   distribution makes it eligible for export under the License Exception
   ENC Technology Software Unrestricted (TSU) exception (see the BIS
   Export Administration Regulations, Section 740.13) for both object
   code and source code.

   The following provides more details on the included cryptographic
   software:

   Apache Rampart   : http://ws.apache.org/rampart/
   Apache WSS4J     : http://ws.apache.org/wss4j/
   Apache Santuario : http://santuario.apache.org/
   Bouncycastle     : http://www.bouncycastle.org/

--------------------------------------------------------------------------------
(c) Copyright 2012 WSO2 Inc.

