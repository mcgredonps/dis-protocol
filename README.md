## DIS Protocol

This contains a computer-readable description of the DIS protocol. 

The XML document describes the PDUs and records in the DIS
protocol. This is used as an input to the xmlpg program, 
which can generate Java, C++, C#, an Objective-C source
code. 

The XML format is relatively straightforward. The document
describes classes and their attributes. The attributes can
be the various primitive types (byte, short, int, long,
float, double, etc). They can also be arrays or variable
length lists of primitives or objects. A special type
of primitive is a count field, which contains a number
that tells us how long a later variable length list is. 

The format is rather lightly documented, and is only well-formed
XML; there is no schema. In the end the documentation is primarily
in the XMLPG source code.

Documents include:

DIS1995.xml: The DIS-1995 standard, the original IEEE 1278.1.
DIS1998.xml: Revised DIS standard
DIS2009.xml: The updated IEEE format, whith additions for 
             directed energy and some name changes in the API


