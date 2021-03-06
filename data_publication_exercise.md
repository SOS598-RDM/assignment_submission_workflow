# SOS 598 Research Data Management: data publishing exercise

1. [overview](https://github.com/SOS598-RDM/assignment_submission_workflow/blob/master/data_publication_exercise.md#overview)
2. [accessing and navigating HDD](https://github.com/SOS598-RDM/assignment_submission_workflow/blob/master/data_publication_exercise.md#accessing-and-navigating-hdd)
3. [adding your data set](https://github.com/SOS598-RDM/assignment_submission_workflow/blob/master/data_publication_exercise.md#adding-your-data-set)
4. [add data file(s)](https://github.com/SOS598-RDM/assignment_submission_workflow/blob/master/data_publication_exercise.md#add-data-files)
5. [save and add collaborators](https://github.com/SOS598-RDM/assignment_submission_workflow/blob/master/data_publication_exercise.md#save-and-add-collaborators)

## overview

In this exercise, you will submit a well-documented set of your own data (or
data related to your research) to [Harvard's demo dataverse
(HDD)](https://demo.dataverse.org/). HDD is a development or scratch environment
version of the University's dataverse repository - please be sure that you
address this exercise in the demo environment!

The infrastructure and metadata standard that HDD employs does not accommodate
metadata for individual data files. An implication of this limitation is that we
are unable to add metadata, such as the meaning of columns in our tabular data,
units of measure, missing value codes, or factor levels for each data file. One
approach to adding these critical metadata is to include the details in the data
files themselves. For this exercise, use the approach that we went through in
class to add metadata as a yaml header at the top of your data file - these
details can be written by hand, with the R csvy package, or some combination of
the two. Please revisit the GitHub
[repository](https://github.com/SOS598-RDM/rdm-lecture-metadata) for a review of
our work in class.


## accessing and navigating HDD

ASU has an institutional affiliation with the Harvard dataverse so you will use
ASU's ASURITE system to access HDD. Once you have authenticated with ASURITE by
logging into MyASU or your ASU email, you can log into HDD by identifying
Arizona State University as your institution.

A dataverse (a collection of datasets) has been created within HDD for this
course, and is where you will publish your data set. Please see [link
to](https://demo.dataverse.org/dataverse/ASU_SOS_RDM_2019) link or search for
*ASU_SOS_RDM_2019* within HDD to locate the dataverse for this class.


## adding your data set

Once you have logged into HDD and navigated to the class dataverse, you can
begin the process of adding your data set by clicking the `Add Data` button, and
selecting `New Dataset`.

<br>
<hr>

![add_data](data_publication_figures/add_data.png)

<hr>
<br>

Add appropriate metadata for your data set using the web-based form. The
metadata contributed through the web form (e.g., title, author(s), keyword(s),
etc.) will be associated with any and all data files added to this data set, so
we can think of these metadata as being at the level of the data set. Note the
ability to add additional metadata, such as geospatial details, by expanding
additional sections at the bottom of the form.


## add data file(s)

HDD does not accommodate metadata for individual data files so metadata, such as
how to interpret columns of tabular data, must be added to the file itself
outside of HDD as noted above. Select and upload your data file(s), which should
contain relevant metadata as a yaml header, in the Files dialog box of the web
form.

<br>
<hr>

![upload_files](data_publication_figures/upload_files.png)

<hr>
<br>


## save and add collaborators

After having added appropriate metadata using the web-based form, added data
file(s), and reviewed the information for completeness and accuracy, save your
data set with the `Save Dataset` button at the bottom of the form. Once saved,
add Stevan and Philip as curators to your data set so that we are alerted of
your submission and can access the information.

**add curators by first editing permissions of the data set: `Edit` > `Permissions` > `Dataset`**
<br>
<hr>

![edit_permissions](data_publication_figures/edit_permissions.png)

<hr>
<br>

**then assigning Users/Groups: `Assign Roles to Users/Groups`.** Because of the
association with ASU, our names are registered in the system and searchable in
the dialog box. Save changes, and you are done.

<br>
<hr>

![assign_curator_roles](data_publication_figures/assign_curator_roles.png)

<hr>
<br>
