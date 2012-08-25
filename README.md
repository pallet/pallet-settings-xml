# pallet-settings-xml

Many pallet projects use maven for building, and the `pom.xml` files for these
do not include repository information. This project provides a settings.xml file
that can be used to build pallet projects.

e.g. to run tests:

```
mvn --settings settings.xml test
```
