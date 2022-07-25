# EaglerMavenRepo

This repository contains a GitHub Maven repository that can be used for common plugin dependencies that plugins for Eaglercraft servers can use.

# Contributing

If you would like to contribute and suggest some plugins to be added, please **do not** submit a pull request. Instead, submit an issue with the plugin you would like to see added, and we will fetch the relevant version and add it.

**Things you can contribute via pull request:**
- Fixing typos in readme
- Fixing the ass structure of the Readme
- Basically fixing the readme
## How to use:

Include the repo in your pom.xml in your repositories with:
```
<repository>
    <id>PrimCoreRepos-repos</id>
    <url>https://github.com/darverdevs/EaglerMavenRepo/raw/main</url>
</repository>
```
Then, add the craftbukkit jar file to your pom with:
```
<dependency>
    <groupId>com.github.EaglerMaven</groupId>
    <artifactId>craftbukkit</artifactId>
    <version>1.5.2-R1.0</version>
</dependency>
```
Or, alternatively, you can use BongoBukkit which has a vehicleSteerEvent
```
<dependency>
    <groupId>com.github.EaglerMaven</groupId>
    <artifactId>BongoBukkit</artifactId>
    <version>1.5.2</version>
    <scope>provided</scope>
</dependency>
```
Finally, to add Plugin API as dependencies:
```
(Not: you do not have to add all of the dependencies for anything to work)
---------- Vault -----------
<dependency>
    <groupId>com.github.EaglerMaven</groupId>
    <artifactId>Vault</artifactId>
    <version>1.2.26</version>
</dependency>
---------- MassiveCore -----------
<dependency>
    <groupId>com.github.EaglerMaven</groupId>
    <artifactId>MassiveCore</artifactId>
    <version>6.4.1</version>
</dependency>
---------- Factions -----------
<dependency>
    <groupId>com.github.EaglerMaven</groupId>
    <artifactId>Factions</artifactId>
    <version>2.0.1</version>
</dependency>
---------- EffectLib -----------
<dependency>
    <groupId>com.github.EaglerMaven</groupId>
    <artifactId>EffectLib</artifactId>
    <version>3.0</version>
</dependency>
---------- ProtocolLib -----------
<dependency>
    <groupId>com.github.EaglerMaven</groupId>
    <artifactId>ProtocolLib</artifactId>
    <version>3.6.4</version>
</dependency>
--------- PermissionSex ----------
<dependency>
    <groupId>com.github.EaglerMaven</groupId>
    <artifactId>PermissionSex</artifactId>
    <version>1.19.6</version>
</dependency>
--------- BossBarAPI -------------
<dependency>
    <groupId>com.github.EaglerMaven</groupId>
    <artifactId>BossBarAPI</artifactId>
    <version>0.0.1</version>
    <scope>provided</scope>
</dependency>
```

If you are getting errors, run `mvn clean install -U` then, cut and paste the dependencies
