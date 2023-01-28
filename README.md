# Project Proposal
### **Title**: FaceLook
### **Author**: Allen Li
<br>

### **What and why**:
It is too easy for bad actors to misuse headshots of other people as their own profile pictures online. This enables a multitude of impersonation scams, resulting in unwitting victims giving personal information or money to people they thought were using legitimate profiles. While *Google Images* reverse search can be used to try to find the original headshot (if it was indeed appropriated by a bad actor) and thereby detect misleading profiles, it isn't foolproof; it usually only uncovers similar versions of the image, *if* it can find them.

*FaceLook* will be a dedicated face lookup website--users can upload profile headshots and verify whether they belong to the account using them. Users will also be able to submit reports of stolen or otherwise falsified profile pictures, which (if verified) can then be used to improve *FaceLook*'s scope and accuracy. 

With *FaceLook*, users can identify suspicious profiles and help others do so with crowdsourced reporting. This will make it harder for bad actors to misuse headshots to mislead people, and so make the Internet a little safer.
<br>

### **For whom**:
*FaceLook* is intended for the general public, especially those on communication platforms in which users want be sure of other users'
identities (e.g. LinkedIn). 
<br>

### **How**:
*FaceLook* will allow users to upload the profile headshot they want to look up, along with information about where they found the image. If the headshot (or a variation of it) is being used on a false profile, *FaceLook* will return information about who the headshot actually belongs to, as well as statistics including where else (i.e. other websites) and how many other times the headshot was misused.

If no variation of the uploaded image can be found, but the user has reason to believe it is part of a fake profile, they can submit the image, the query information, and justification as a report. Reported images, after verification, will be added to *FaceLook*'s database for other users to see. Because links can change or image variations can arise, users can also submit reports to correct a record on *FaceLook*. Users must be registered in order to submit reports, but don't have to be for the lookup service.
<br>

### **Scope**:
A prototype *FaceLook* would require a UI capable of taking user queries in the form of an uploaded image and other textual information, and returning results (using the image as a key) from the known image database. This image database, along with a registered users database, comprise the backend. The main difficulty would appear to be matching the queried image against those stored in the database for similarity, but this can be accomplished with libraries such as *pixelmatch*.
