# Getting-Started
This document provides information on initial compliancy measures and how to gain access to the RCE 

Granting RCE Access
Granting an individual access to the RCE is a multi-step process that must be followed carefully to ensure that access is vetted and documented. The process differs depending on whether access is limited to the general tier, or whether access to the open health access tier is required. The process for the two access tiers are described below.

General Access Tier
This is the tier that most new users should be included in. This tier included open access to all exposure and confounder data, with access to individual health datasets available by request. This allows us to more easily track who has access to what data, and lets us implement finer access controls than the UNIX groups of the RCE allow.

Users in this group should have access to the following spaces:

ci3_exposure
ci3_confounders
nsaph_common
ci3_<username>
Pre-request checklist
Before granting access verify that the following conditions are met:

 The individual's identity, affiliation, and role have been verified.
 Francesca Dominici has approved the request in writing.
Access request template
Once the pre-request checklist has been completed, open a ticket with RCE support staff (support@rce.hmdc.harvard.edu), cc'ing the email of the new user, and requesting for a new account to be created with access to project spaces determined by access tier.

The standard email to support for this tier looks like the following:

"Hi all,

(cc'd) is a new NSAPH collaborator. Can we please create a new NSAPH RCE account for <new_user>, and grant them access to ci3_exposure, ci3_confounders, nsaph_common, and their ci3_ directory?

Thanks,

..."

Post-request checklist
 Verify that the user account has been created and / or added to the requested groups.
 Email the user welcoming them to the team and linking them to NSAPH. Include links to RCE guides and the Analytic Data Use Agreement form.
 Request the user's Github.com user name (ask them to create one if they don't have an account already) and add them to the researcher team at https://github.com/orgs/NSAPH/people.
 
Open Health Access Tier
This is a tier for users that have a need to have access to all currently available health data sets, not solely ones created for a specific project. This tier includes access to all data in the general access tier, plus ci3_analysis and the library of analytic data sets in ci3_health_data. The total list of spaces that users in this tier should have access to is the following:

ci3_exposure
ci3_confounders
ci3_analysis
ci3_health_data
nsaph_common
ci3_<username>
Pre-request checklist
Before granting access verify that the following conditions are met:

 The individual's identity, affiliation, and role have been verified.
 Francesca Dominici has approved the request in writing.
 Ensure that the requester has an up to date CITI certification.
 Verify that the individual is authorized to access health data. Checklists need to be developed for this, for now best to check with Yun Wang at mailto:yunwang@hsph.harvard.edu.
Access request template
The standard email requesting access for a user in this tier looks like the following:

Hi all,

(cc'd) is a at (S)He is a new NSAPH collaborator. Can we please create a new NSAPH RCE account for <new_user>, cc'd, and grant them access to ci3_analysis, ci3_health_data, ci3_exposure, ci3_confounders, ci3_nsaph_common, and their ci3_ directory?

Thanks,

...

Post-request checklist
 Verify that the user account has been created and / or added to the requested groups.
 Email the user welcoming them to the team and linking them to NSAPH. Include links to RCE guides and the Analytic Data Use Agreement form.
 Request the user's Github.com user name (ask them to create one if they don't have an account already) and add them to the researcher team at https://github.com/orgs/NSAPH/people.
Granting access to a health data set
When someone requests access to a new health data set, the following steps should be taken:

 Ask the requester to fill out a copy of Analytic Data Use Agreement.docx describing the data that they're interested in, and agreeing to the data access principles. Verify that the form is filled out completely.
 Obtain written authorization for data access from Francesca Dominici.
 Ensure that the requester has an up to date CITI certification.
 Verify that the individual is authorized to access health data. Checklists need to be developed for this, for now best to check with Yun Wang at mailto:yunwang@hsph.harvard.edu.
 If the requested dataset is available, copy the data and assosciated documentation to a directory in the requester's ci3_username directory.
 If the dataset is not available, determine if the requested data can be assembled from currently available datasets. If it can, create a project to assemble the data set. If not, ask for the requester to submit a new data request to Yun.
 Update https://github.com/NSAPH/data_requests/blob/master/project_list.md with the information from the Analytic Data Use Agreement.
 Update https://github.com/NSAPH/data_documentation/blob/master/rce_data_list/health_data.csv as needed. Make sure to add links to the Analytic Data Use Agreement information from the previous step.
