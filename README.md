# Web3 Monitoring data Schemas
 
Web3 Monitoring platform schemas definition in Avro format.

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

* AlertEvent.avsc
* BlockEvent.avsc
* ContractEvent.avsc
* EventBlock.avsc
* TransactionEvent.avsc

