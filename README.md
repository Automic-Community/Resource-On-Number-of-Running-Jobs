*Resource On Number of Running Jobs*
=============


Counts the number of running jobs.
http://github.com/Automic-Community/Resource-On-Number-of-Running-Jobs

<!-- List of attached files -->
Contents of Solution Package:

						
								*Number_of_Running_Jobs.zip
								
						


Documenation and Instructions
---

<div class="ipsType_textblock ipsPad_half description_content"><span><strong class="bbc">Description:</strong></span><br /><br />Resource for Dollar Universe 6.<br /><br />Counts the number of running jobs when used in order to ensure that the maximum number of executing jobs has not been reached.</div>
<div class="ipsType_textblock ipsPad_half description_content">&nbsp;</div>
<div class="ipsType_textblock ipsPad_half description_content">
<p><strong class="title">Target environments:</strong> Linux / Unix</p>
<p><strong class="title">Prerequisites:</strong> DU6</p>
</div>
<div class="ipsType_textblock ipsPad_half description_content"><br /><strong class="bbc"><span>Content:</span></strong><br /><br />1 Administration Object Package containing an sh script that will be inserted on the node as a nodefile, (in charge of checking the number of running jobs)<br />1 Regular Package containing the Dollar Universe resource object which calls the script (mentioned above)<br /><br /><br /><strong class="bbc">Installation:</strong><br /><br />Insert both packages into Dollar Universe<br /><br /><strong class="bbc">Usage:</strong><br /><br />Edit the inserted resource in order to fill out parameters for the script (by default there is only one parameter with value of 2)<br /><br />Parameter 1: [mandatory] Upper limit for number of current running jobs (if the actual number is above the limit, the resource stays in event wait)<br />Parameter 2: [Optional], remote node name (if unspecified, the node name used is the local one)</div>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
