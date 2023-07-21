Once installed, to run the Datcom+ or Datcom+ Pro program, you just double-click on one of the Datcom Input Files (with .dcm extension) in the Examples directory. If you just try to run the digdat.exe program alone, it will not run correctly, and give you error messages such as “open: No such file or directory” and “apparent state: unit 5 named for005.dat”. This may also cause global warming.

B737 model warning: This model came from the NASA reports on Datcom from the 1970’s Their model is garbage. The wing airfoil is nowhere close to correct. While finding the exact airfoil is not possible, you can surely find something better than this symmetric airfoil.

Some users running the free version of Datcom+ under Windows 10 have reported problems where a message says “Error located in file: Citation.dcm” when they double-click on a .DCM file, but it doesn’t happen to all users. I haven’t figured out when it is triggered. If it happens to you, follow these steps:

1.  After installing the Datcom+ package, Press Windows key + r. Type in “SystemPropertiesAdvanced.exe”.

2.  Click on the Environment Variables box.

3.  Change the environment variable for DATCOMROOT, removing the leading and trailing double-quote. Save and get out of this.

4.  In the Datcom\bin directory on your desktop, edit the Datcom.bat file. On lines 14, 15, and 16, remove the double-quotes (leading and trailing).

   set PREDAT_PROGRAM="predat"

   set DATCOM_PROGRAM="digdat"

   set DATCOM_MODELER_PROGRAM="datcom-modeler"

5.  You should be able to run the programs now.

 cc: http://www.holycows.net/datcom/buy.html
