# SOS 519/598 Research Data Management: data-publishing exercise

1. [overview](https://github.com/SOS598-RDM/assignment_submission_workflow/blob/master/data_publication_exercise.md#overview)
2. [accessing and navigating HDD](https://github.com/SOS598-RDM/assignment_submission_workflow/blob/master/data_publication_exercise.md#accessing-and-navigating-hdd)
3. [adding your data set](https://github.com/SOS598-RDM/assignment_submission_workflow/blob/master/data_publication_exercise.md#adding-your-data-set)
4. [add data file(s)](https://github.com/SOS598-RDM/assignment_submission_workflow/blob/master/data_publication_exercise.md#add-data-files)
5. [save and add collaborators](https://github.com/SOS598-RDM/assignment_submission_workflow/blob/master/data_publication_exercise.md#save-and-add-collaborators)

## overview

In this exercise, you will submit a well-documented set of your own data (or data related to your research) to [Harvard's demo dataverse (HDD)](https://demo.dataverse.org/). HDD is a development or scratch environment version of the University's dataverse repository - please be absolutely certain that you address this exercise in the *demo* environment!

The infrastructure and metadata standard that HDD employs does not accommodate metadata for individual data files. An implication of this limitation is that we are unable to add metadata, such as the meaning of columns in our tabular data, units of measure, missing value codes, or factor levels for each data file. There are several approaches to addressing these critical metadata, such as embedding the metadata in the data file, or adding structured (e.g., frictionless) or unstructured (e.g., a README) metadata in an accompanying metadata file. Please review the materials in [generating metadata for tabular and non-tabular data resources](https://github.com/SOS598-RDM/rdm-lecture-metadata/blob/master/data/stream_chemistry_metadata.md) for an overview of different approaches.

## rubric

[ ] dataset:   features a rich title that conveys dataset subject, and, as much as possible, geographic and spatial extent
[ ] dataset:   includes relevant, domain-specific keywords that will optimize user search and retrieval
[ ] dataset:   features overview documentation detailing the nature of the study, study objectives, and other relevant aspects of the study
[ ] dataset:   includes methods documentation detailing how data were collected and/or generated
[ ] dataset:   includes author details, including name, email, and ORCiD
[ ] dataset:   dates in metadata textual descriptions, and within data conform to ISO standards
[ ] data:      well-structured (tidy)
[ ] data:      the meaning of special characters, such as those representing missing values, are articulated clearly
[ ] variables: meaning of each variable is articulated clearly
[ ] variables: if relevant, units of each variable is articulated clearly

## accessing and navigating HDD

ASU has an institutional affiliation with the Harvard dataverse so you will use ASU's ASURITE system to access HDD. Note that you *may* need to have enabled the ASU VPN if attempting to access the HDD from an off-campus network. Once you have authenticated with ASURITE by logging into MyASU or your ASU email, you can log into HDD by identifying Arizona State University as your institution.

A dataverse (a collection of datasets) has been created within HDD for this course, and is where you will publish your dataset: [ASU_SOS_519](https://demo.dataverse.org/dataverse/ASU_SOS_519) (or search for ASU_SOS_519 with the HDD). 


## adding your data set

Once you have logged into HDD and navigated to the class dataverse, you can begin the process of adding your data set by clicking the `Add Data` button, and selecting `New Dataset`.

<br>
<hr>

![add_data](data_publication_figures/add_data.png)

<hr>
<br>

Add appropriate metadata for your data set using the web-based form. The metadata contributed through the web form (e.g., title, author(s), keyword(s), etc.) will be associated with any and all data files added to this data set, so we can think of these metadata as being at the level of the data set. Note the ability to add additional metadata, such as geospatial details, by expanding additional sections at the bottom of the form.


## add a data file

Select and upload your data file. Depending on how you constructed metadata to describe the contents of your data file (see below), upload accompanying metadata file(s) if and as appropriate.

<br>
<hr>

![upload_files](data_publication_figures/upload_files.png)

<hr>
<br>

### data-resource metadata

HDD does not accommodate metadata for individual data resources. That is, there is not a way to associate metadata about a data resource with the data resource explicitly. For example, I cannot upload a tabular data file then describe the meaning of variables, units of observation, missing value codes, or other details of that tabular data resource directly in the HDD environment. As such, we need to provide metadata about our data resources using alternate approaches. One way to do this *within* HDD would be to provide data-resource metadata using one or more DESCRIPTION metadata fields in HDD. However, that is not optimal as the DESCRIPTION metadata field is intended to provide metadata about the study generally. Another approach would be to embed metadata directly in the data file, such as using the [csvy](https://csvy.org/) approach that we reviewed in class. Yet another approach is to include files that contain data-resource metadata in accompanying files. An accompanying metadata file could be in the form of a well-structured, thoughtfully crafted README or something more structured such as a json file corresponding to the [frictionless](https://frictionlessdata.io/) schema. Please see the course [resource](https://github.com/SOS598-RDM/rdm-lecture-metadata/blob/master/data/stream_chemistry_metadata.md#iii-include-metadata-in-a-well-constructed-readme) on this topic for a more comprehensive overview.

## save and add collaborators

*Note for fall **2021 RDM students**: adding collaborators is not an option with the current suite of permissions so please just save your datasets when complete as noted below - no need to add collaborators.*

After having added appropriate metadata using the web-based form, added your data file (and metadata file is appropriate), and reviewed the information for completeness and accuracy, save your data set with the `Save Dataset` button at the bottom of the form. Once saved, add me as a curator to your data set so that I am alerted to your submission and can access the information.

**add curators by first editing permissions of the data set: `Edit` > `Permissions` > `Dataset`**

<br>
<hr>

![edit_permissions](data_publication_figures/edit_permissions.png)

<hr>
<br>

**then assigning Users/Groups: `Assign Roles to Users/Groups`.** Because of the association with ASU, our names are registered in the system and searchable in the dialog box. Save changes, and you are done.

<br>
<hr>

![assign_curator_roles](data_publication_figures/assign_curator_roles.png)

<hr>
<br>
