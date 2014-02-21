DataNucleus JDO NuoDB Sample
========

[<img src="https://api.travis-ci.org/nuodb/datanucleus-nuodb-sample.png?branch=master" alt="Build Status" />](http://travis-ci.org/nuodb/datanucleus-nuodb-sample)

# Description

Simple demonstration of using JDO with DataNucleus against NuoDB using BoneCP.

Maven Instructions
==================
1. Run the command *mvn clean compile*. This builds everything and enhances the
   classes.

2. Run the command *mvn datanucleus:schema-create*. This creates the schema for
   the tutorial.

3. Run the command *mvn exec:java*. This runs the tutorial.

4. Run the command *mvn datanucleus:schema-delete*. This deletes the schema for
   the tutorial
