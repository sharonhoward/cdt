Middlesex Convicts Delivered For Transportation, 1785-1792
====================


Introduction
-------------

Between July 1789 and October 1792 the keeper of Newgate gaol, Richard Akerman, submitted to the Justices of the Peace at the Middlesex Sessions of the Peace a series of lists of convicts sentenced to transportation whom he had conveyed from Newgate to various vessels along the Thames or south coast ports, along with his detailed accounts of the substantial expenses incurred in the process. After the JPs approved his claims and made orders for payment, the names of the convicts and (in most cases) their destinations were neatly copied into the Sessions Order Books. After October 1792 the expenses continued to be periodically recorded in the Order Books, but not the convicts' names. 


Coverage and Context
--------------

Akerman's lists named a total of 1515 offenders convicted at the Old Bailey and Middlesex Sessions (the lists do not contain details of individuals' trials) whom he conveyed from Newgate and delivered to a number of destinations between January 1785 and July 1792. Not all of the 1515 actually embarked for Australia, but it is likely that the vast majority did so. Thus, the lists chronicle the very beginnings of the enforced emigration of, ultimately, more than 160,000 offenders from Britain to Australia between 1787 and 1868, and they document a stage of the convicts' long journey for which there are few surviving records earlier than the 19th-century prison hulk registers held at The National Archives (primarily TNA HO8-9, ADM6). 

They also complement the earliest Home Office Criminal Registers (TNA HO26) which have also been digitised by [London Lives](http://www.londonlives.org/static/CR.jsp). The next stage of the voyage is covered by the [Convict Transportation Registers](http://www.slq.qld.gov.au/resources/family-history/convicts), indexed by the State Library of Queensland; and by the earliest convict indents, which have been digitised and indexed by the [New South Wales State Archives](https://www.records.nsw.gov.au/state-archives/indexes-online/indexes-to-convict-records/index-to-early-convict-records). 

Record linkage will be carried out on the dataset by the [Digital Panopticon project](http://www.digitalpanopticon.org), in order to link as many of the names as possible to these related records and to the [Old Bailey Proceedings](http://www.oldbaileyonline.org). The resulting linked data will also be made freely available at a later stage.  


License
--------

The dataset and this documentation are licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

This means that you are free to copy and redistribute the material in any medium or format; and to remix, transform, and build upon the material for any purpose, even commercially, providing you follow the terms of the licence:

* You must give appropriate credit, provide a link to the license, and indicate if changes were made. 
* If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original. 


Citation
---------

Suggested format for academic citation:

Sharon Howard, 'Middlesex Convicts Delivered for Transportation 1785-92', *London Lives, 1690-1800* (2015).


Acknowledgments
--------------------

The dataset has been created using the transcriptions of the Order Books published at the [London Lives website](www.londonlives.org). Further general background information on the Order Books can also be found at [the London Lives website](http://www.londonlives.org/static/GO.jsp). I am grateful to Tim Hitchcock and Bob Shoemaker, the London Lives project directors, for agreeing to share this data.
        
The original documents are held at the London Metropolitan Archives, part of the Middlesex Sessions Records series (MJ/OC/11-12).

The data was created while working on the [Digital Panopticon project](http://www.digitalpanopticon.org), funded by the Arts and Humanities Research Council.


The Data
----------

The data file **LondonLives_delivered_convicts_201511.csv** contains the name, aliases and gender of each prisoner; the delivered date and, where named, the contractor, ship or hulk, and location; the date of the court session at which the list was presented; and the necessary identifiers to link the data back to London Lives. 

Some transcription and tagging errors have been corrected, but it is likely that less obvious ones remain. London Lives URLs have been included in the data to facilitate checking against the images of the original pages; . 

### cdt_id

Dataset unique identifier.
 
### ll_id

The unique identifier for the prisoner in the London Lives database.  

###  ll_img

The identifier for the image in which the prisoner appears.

###  ll_url

The URL of the page in which the prisoner appears.

###  session_date

The date (month and year) of the court session at which Akerman submitted the list containing the convict's name, as given in the order book. (This is completely unrelated to the date of the convict's trial, which is never given.)

###  pris_number

The prisoner's number in the list. (It is unlikely that the numbers had any particular significance but they aid quick location of individuals within a page.) 

###  given

The prisoner's first name(s).

###  surname

The prisoner's surname(s).

###  alias

The prisoner's alias(es), if any.

###  other_info

Any other descriptive information provided about the prisoner.

###  gender

The prisoner's gender, derived from their given name and/or position in the lists (men and women were mostly listed separately).

###  del_date

The date on which the prisoner was delivered (yyyy-mm-dd). 

###  del_to_whom

If named, an individual into whose custody the prisoner was delivered, usually the contractor responsible for overseeing the transportation of the convicts.

###  del_where

If stated, the location to which the prisoner was delivered. 

###  del_to_ship

If stated, the name of the ship or hulk to which the prisoner was delivered. 
