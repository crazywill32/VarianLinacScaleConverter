# VarianLinacScaleConverter
A library containing a hand-rolled implementation of the conversion for Varian Linac Display Scales in C#.

# Description
Contains a single class that converts between arbitrary linac scales and a fixed scale defined at initialization. This allows for quick conversion for multiple linacs.
Also contains a through library of test conversions for each scale conversion. The project does not use any ESAPI functions so it can be plugged in anywhere.
The inital commit from this library was taken after I wrote the project in another project. So there is no history on it. 

# Current Limitations
* I was unable to verify the Couch Conversions for the Varian IEC scale. I personally have never seen it.
* Only allows for a single output coordinate systems defined at object instantiation
