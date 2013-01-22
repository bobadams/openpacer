openpacer
=========

A Bill to Open PACER

Clone the repository and open openpacer_bill.xml in a browser.

See the dtd for more explanation of fields.

To make an HTML version of the bill, on the command line, use xsltproc:
xsltproc ./billres.xsl ./openpacer_bill.xml > openpacer_bill.html

xsltproc is already installed in OS X and most Linxux distros, but get it for other OS's here:
http://xmlsoft.org/XSLT/xsltproc2.html

More drafting info here:
http://xml.house.gov
http://www.gpo.gov/fdsys/bulkdata/
http://www.gpo.gov/fdsys/bulkdata/BILLS/resources/BILLS-XML_User-Guide-v1.pdf
