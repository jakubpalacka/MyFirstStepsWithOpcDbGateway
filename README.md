# My First Steps With OpcDbGateway

## A Step by Step Guide to Creating Basic Applications Using OpcDbGateway

### Introduction

#### What is OpcDbGateway

OpcDbGateway is a software package which allows you to integrate applications to collect, 
process and visualize data from various devices and data sources. 
It can be used for office applications as well as industrial and/or infrastructural ones.

#### How does it Work

The package consists of 2 main parts, the *Runtime* and the *Configuration Application* (*Configurator*). 
The Runtime communicates with different devices or software applications through OPC servers or other communication drivers.
The configurator is actually an application development environment. It allows you to configure data points from external sources e.g. temperature, pressure etc., and map them to memory operands (MO) in the internal process image memory.

#### What can it do

The data in the MOs can be processed using configurable commands and stored in databases or displayed in real time in applications such as Microsoft Excel. The configurator can be used to create applications instead of having to program them in a programming language. To do this you can use Function Blocks (FBs) which contain configurable commands.

### Content

There are four packages included here, labeled 1-4,
each contains a step by step guide and an example configuration of what the application
that is being described in the guide should look like when it is finished. Each application builds on
what was done in the previous one ie. the configuration in Package 2 is an upgraded version of Package 1,
Package 3 is an upgraded version of Package 2 etc. Packages 3 and 4 also includes the necessary MS Acces and Excel documents that are
needed when following the guide.

#### Package 1

Contains:

* Step by step guide to making a basic filter application
* Ready made working configuration as an example

#### Package 2

Contains:

* Step by step guide to upgrading the filter application to a regulator
* Ready made working configuration as an example

#### Package 3

Contains:

* Step by step guide to connecting a database to the regulator where processed values can be stored
* Ready made working configuration as an example
 *MS Acces database "ProcessDB" which is already connected to the example configuration

#### Package 4

 Contains:

* Step by step guide to connecting an Excel spreadsheet where processed values 
 from the regulator can be displayed in the form of a graph
* Ready made working configuration as an example
* MS Access database "ProcessDB" which is already connected to the example configuration
* MS Excel spreadsheet which is already connected to the example configuration and has a graph already set up.

**Note: The connection string for the MS Access database will need to be changed
 to match the location of where it is currently stored on your computer**

If this is the first time you are using OpcDbGateway I recommend
 starting out with Package 1 and working through to Package 4