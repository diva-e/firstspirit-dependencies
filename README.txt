## Description
This is a project for including FirstSpirit artifacts in maven projects.


## Installation
* Maven is required
* Git is required
* Clone project via git because no public artifact is available.

### Via Maven Repo (local or remote)
#### Maven
`<dependencyManagement>
 	<dependencies>
 		<dependency>
 			<groupId>com.diva-e.firstspirit</groupId>
 			<artifactId>firstspirit-dependencies</artifactId>
 			<version>1.0.3</version>
 			<type>pom</type>
 			<scope>import</scope>
 		</dependency>
 	</dependencies>
 </dependencyManagement>`

`<dependencies>
 	<dependency>
 		<groupId>de.espirit.firstspirit</groupId>
 		<artifactId>fs-api</artifactId>
 		<scope>provided</scope>
 	</dependency>
 	...
 </dependencies>`