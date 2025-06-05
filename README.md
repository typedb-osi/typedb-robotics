# Robotics

## Introduction

This repository shows how to use TypeDB for robotic navigation of the world. It is based on a real-world usage developed by Joris Sijs at the TNO University.

The database schema uses TypeDB 3.0.

## Setup

The easiest way to load this example is using TypeDB Console.

1. Boot up TypeDB 3.0
2. Run the TypeQLScript setup script `setup_script.tqls` via console:
```
typedb console --address=<address> --username=<username> --script=<path to setup_script.tqls>
```
  - Note: some versions of Console didn't yet support relative paths in Scripts - if that is the case, please update the paths inside the `setup__script.tqls` to be absolute

This will setup a database named `robotics` and load the schema and sample data.

Have fun!

## Example Queries

TODO!

