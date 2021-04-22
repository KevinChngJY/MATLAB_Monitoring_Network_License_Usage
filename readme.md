## Monitoring the Network License Usage of MATLAB (Drafting)
Authors : Kevin Chng (Email Address : kevin.chng@techsource-asia.com)

In MATLAB, there are 2 main types of Network Licenses which are Network Named User License and Concurrent User License. 
For managing a group/large quantities of MATLAB licenses, understanding the usage of licenses is important as it could be the decisive factor for your license renewal or purchasing.
Besides, you could optimize the usage of license by allocating the NNU license to heavier user.

---

## SECTION 1 : Get the server log file and option file from license manager
In your license server machine, open lmtools (Consult your server engineer/license administrator if you don't know the location)
by default, it is located in MATLAB_Installation_rootfolder\MATLAB_version\etc\win64 (Window) or MATLAB_Installation_rootfolder/MATLAB_version/etc/glnxa64 (linux).

<img src="images/image1.png"
     style="float: left; margin-right: 0px;" />
