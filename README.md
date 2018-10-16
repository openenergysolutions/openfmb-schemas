# openfmb-schemas

Schemas generated from the OpenFMB UML model using exporter plugins.

Versions are currently being maintained by a date tag in the format <year>-<month>-<day>

## protobuf

The */protobuf* directory contains a set of files for using OpenFMB serialized using Google [Protocol Buffers](https://developers.google.com/protocol-buffers/). The protobuf compiler is open source and can generate bindings in a number of target languages.

## IDL

The */idl* directory contains an IDL schema file for using OpenFMB inconjunction with a DDS implementation such as those from [RTI](https://www.rti.com/) or [TwinOaks](http://www.twinoakscomputing.com/). The IDL requires a commercial compiler.
