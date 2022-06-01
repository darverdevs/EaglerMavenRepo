# EaglerMavenRepo

This repository contains a GitHub Maven repository that can be used for common plugin dependencies that plugins for Eaglercraft servers use.

# Contributing

If you would like to contribute and suggest some plugins to be added, please **do not** submit a pull request. Instead, submit an issue with the plugin you would like to see added, and we will fetch the relevant version and add it.

**Things you can contribute via pull request:**
- Fixing typos in readme
- Fixing the ass structure of the Readme
- Basically fixing the readme
## How to use:

Include the repo in your pom.xml with:
```
<repository>
    <id>PrimCoreRepos-repos</id>
    <url>https://github.com/darverdevs/EaglerMavenRepo/raw/main</url>
</repository>
```

Then, to add them as dependencies:
```
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
```

If you are getting errors, run `mvn clean install -U` then, cut and paste the dependencies
