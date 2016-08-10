## RxJava-AppDynamics


## Information
| Package       | Description   | Version|
| ------------- |:-------------:| ------:|
| rxjava-appdynamics| Hooks for Appdynamics to instrument rxjava streams | 1.0.0-rc1 |

# Overview
rxjava-appdynamics provides specific hooks for Appdynamics to instrument rxjava streams
# Usage
Maven:

```
<dependency>    
    <groupId>net.kenzan.rxjava</groupId>
	<artifactId>rxjava-appdynamics</artifactId>
	<version>0.0.1-SNAPSHOT</version>
</dependency> 
```
# Dependencies
| GroupId   | ArtifactId    | Min. Version |
| --------- |:-------------:| ------------:|
| io.reactivex |  rxjava   |  1.1.1  |

# Hooks for Appdynamics
- onCreate: via AppdOnSubscribe
- onSubscribeStart: via AppdOnSubscribe
- onLift: via AppdOperator
- onSubscribeReturn: via AppdSubscription

