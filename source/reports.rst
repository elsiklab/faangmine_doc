Report Pages
============

.. role:: raw-html(raw)
    :format: html
.. |rightArrow| unicode:: U+2B95

All objects in FAANGMine (e.g., gene, protein, transcript, publication) have report pages that can viewed after running a query.  It allows users to view all available information for that object while providing links to related objects.  As an example, we can revisit the templates example.  In the list of templates under the **Templates** tab on the FAANGMine home page, select **Gene** |rightArrow| **Homologues** to query FAANGMine to retrieve all homologues for a given gene. Enter "GSTM1" into the the LOOKUP search box then click **Show Results**.  In the results table, note that every entry is contains a link.  You can mouse over any link to bring up a summary of that object. If we hover over the first Gene ID, we can see a summary box for that gene.

.. figure:: images/reports-summary.jpg
   :alt: Report summary box
   :figclass: align-center
   
   Summary for gene entry in query results table
   
..

Clicking on that same item will bring up its report page that includes a comprehensive for gene GSTM1.  The report page header shows the Gene ID and its Biotype, for this example, protein coding. The tabs at the top of the page in the Quick Links menu bar quickly bring you to the data listed. The column on the right side of the report page displays external links to other Mines and databases.

.. figure:: images/reports-page.jpg
   :alt: Report page
   :figclass: align-center
   
   Report page for protein-coding gene
   
..

The content of the report page is divided into categories based on the type of information provided for that particular object. Clicking on links within each category bring up more details about the objects of interest.

Summary
~~~~~~~
The **Summary** section near the top of the report provides information on the gene such as its length, chromosome location, and strand information.  Users can also get the complete FASTA sequence of the gene by clicking on the FASTA tab.

.. figure:: images/reports-page-summary.jpg
   :alt: Report page summary section
   :figclass: align-center
   
   Report page summary section
   
..

Alias and DBxref
~~~~~~~~~~~~~~~~

The Alias and DBxref section displays tables of aliases and database cross references for the gene. Click on the gear icon next to **Gene --> Cross References** to expand the table. In this example, the Ensembl gene ID has one cross reference to a RefSeq gene ID.

.. figure:: images/reports-page-dbxref.jpg
  :alt: Report page Alias and DBxref section
  :figclass: align-center

  Report page Alias and DBxref section

..

Transcripts
~~~~~~~~~~~
The **Transcripts** section contains information about the gene model, such as transcripts and exons. Click on "Transcripts", "Exons", or "Coding Sequences" to expand the table under **All Transcripts for Gene**. Links to FASTA files are included where applicable.

.. figure:: images/reports-page-transcripts.jpg
   :alt: Report page transcript section
   :figclass: align-center
   
   Report page transcripts section
   
..

Proteins
~~~~~~~~
The **Proteins** section provides information about the protein product of the gene. The comments section gives a brief description about the protein along with the UniProt accession and links to any outside data sets.

.. figure:: images/reports-page-proteins.jpg
   :alt: Report page protein section
   :figclass: align-center
   
   Report page proteins section
   
.. 


Function
~~~~~~~~

The **Function** section displays Gene Ontology annotations for a gene. Annotations are divided into three categories:

* Cellular Component
* Molecular Function
* Biological Process


The GO terms are displayed along with the evidence code indicating how the annotations were derived.  A results with Pathway information is also displayed if applicable.

.. figure:: images/reports-page-function.jpg
   :alt: Report page function section
   :figclass: align-center
   
   Report page function section
   
..   


Homology
~~~~~~~~

The **Homology** section provides information for all homologues. The first portion displays a summarized view of the homologues reported in different organisms. The next portion provides more detailed information about the homologue, the type of homologue and from which dataset the information was obtained all displayed in a results table. Click the gear icon next to **Gene --> Homologues for report page** to expand the table.

.. figure:: images/reports-page-homology.jpg
   :alt: Report page homology section
   :figclass: align-center
   
   Report page homology section
   
..   


Publications
~~~~~~~~~~~~
The **Publications** section displays a table of publications related to the gene with links to full citations. Click the gear icon next to **Publications** to expand the table.

.. figure:: images/reports-page-publications.jpg
   :alt: Report page publication section
   :figclass: align-center
   
   Report page publications section
   
..


Other
~~~~~
This last section provides miscellaneous information that do not fit into any of the above categories.  This example lists data sets for this gene and the organism.

.. figure:: images/reports-page-other.jpg
   :alt: Report page other section
   :figclass: align-center
   
   Report page other section
   
..


