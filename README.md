General

This framework helps you to retrieve, resize and cache images for Webdynpro applications

--------------------------------------------------------------------------

Copyright

Licenced under GNU GPL

--------------------------------------------------------------------------

Credits

Framework created by Estelle PIGNON and Sebastien GIRAUD

Inspired from work done by Thomas JUNG from SAP and his work on BMP files posted in SCN :
http://scn.sap.com/people/thomas.jung/blog/2007/09/05/abap-bitmap-image-processing-class

--------------------------------------------------------------------------
Version 0.0.4
	Stable release

Version 0.0.3 unstable
	Working around direct file injection and bug fixing

Version 0.0.2
	Licenced under GNU GPL

Version 0.0.1
	Project initialization

--------------------------------------------------------------------------

Installation

1) Use SAPLink (Nugget WD_IMAGE_TOOLS.nugg) or Zaplink (WD_IMAGE_TOOLS.xml) to import the tools into your SAP system
2) Activate the newly created classes if imported with SAPLink (Zaplink did it for you otherwise).
3) Finished

--------------------------------------------------------------------------

Features :

The framework was manually tested on a WebAS 6.20 and successfully
performed the following actions:

- Handling of framework extension to new kinds of object where to retrieve the images (especially for the next point...).
- Reading image from PM documents attached to PM functionnal locations (Extension type TPLNR)
- Modifying GIF, PNG and JPEG files to resize them either proportionaly to height or width or with fixed size
- Generating URL for both image and thumbnail in Web Dynpro application cache
- Handling expiration delay and refreshing URLs only when necessary
- Direct file injection via stream extension

Known issues :

- very poor error handling... this will come soon

Upcomming :

- Simplify framework extension
- Provide a nice specification (English AND French hopefully...)
- Finding a cool name for this project
