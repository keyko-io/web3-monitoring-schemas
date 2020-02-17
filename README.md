# Web3 Monitoring data Schemas
 
Web3 Monitoring platform schemas definition in Avro format.

![W3M Schemas Build](https://github.com/keyko-io/web3-monitoring-schemas/workflows/W3M%20Schemas%20Build/badge.svg)
[![javadoc](https://javadoc.io/badge2/io.keyko.monitoring/schemas/javadoc.svg)](https://javadoc.io/doc/io.keyko.monitoring/schemas)


You can generate the ZIP including the avro schemas and the Java stubs using the following command:

```
mvn clean package
```

After finish in the target folder you will find: 
* The ZIP file including the Avro schemas
* A Jar file including the Java stubs generated using the schemas

## Requirements

* Maven 3
* Java 11

## Dependency

You can include the stubs generated with the schemas including the following dependency:

```
	<dependency>
		<groupId>io.keyko.monitoring</groupId>
		<artifactId>schemas</artifactId>
		<version>0.1.0</version>
	</dependency>
```

## Schemas

The AVRO implementation of the schemas can be found in the **src/main/resources/avro/** folder. This are the schemas implemented:

* AlertRecord.avsc	
* BlockDetailsRecord.avsc	
* BlockRecord.avsc	
* EventBlockRecord.avsc	
* EventDetailsRecord.avsc	
* EventRecord.avsc	
* NumberParameter.avsc	
* StringParameter.avsc	
* TransactionDetailsRecord.avsc	
* TransactionRecord.avsc	
* ViewBlockRecord.avsc	
* ViewDetailsRecord.avsc	
* ViewRecord.avsc
