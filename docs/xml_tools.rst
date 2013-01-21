Working with XML files
======================

Requirements
------------

Install the softwares below:
  - JAVA (add the java path to PATH, in order to run java from any directory in the computer)
  - Saxon
  - XSD or DTD  (add XSD path to PATH, in order to run java from any directory in the computer)
  - XSL files (add XSL files' path to PATH, in order to run java from any directory in the computer)



How to convert XML PMC to XML SciELO
------------------------------------

  - Download the XSL
  - Execute in the command line:

  .. code-block::

    java <SAXON> -o <RESULT_FILENAME> <XML_FILENAME> <XSL_FILENAME>

  E.g.: 

  .. code-block::
   
    java -jar c:/\bin/\saxon_9.2/\saxon9he.jar -o c:/\my_results/\result.html c:/\my_xml_files/\article.xml :/\scielo/\bin/\pmc/\v3.0/\xsl/\sgml2xml/\xml2pmc.xsl



How to validate an XML file
---------------------------



How to preview the article
--------------------------




