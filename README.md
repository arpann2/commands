# Commands
--------------
## Contents

#### 1. [Linux - Ubuntu](#anch1)
#### 2. [Networking](#anch2)
#### 3. [Docker](#anch3)



<a name="anch1">1. Linux - Ubuntu</a>
```java
To get method name within method --> Thread.currentThread().getStackTrace()[1].getMethodName();
```


<a name="anch2"> 2. Networking</a> 
```java
public static String generateRandomEmailAddress() {
       return "qa"+ UUID.randomUUID().toString().replaceAll("-", "")+"@arpan.com";
}
```


<a name="anch3">3. Docker</a>
```java
public static String generateRandomEmailAddressWith10Values() {
return "qa"+ UUID.randomUUID().toString().replaceAll("-", "").substring(0,9)+"@arpan.com";
}
```
