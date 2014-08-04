## Installing Add-On Products
Add-on products are system extensions. You can install a third party add-on product or a special system extension of openSUSE® (for example, a CD with support for additional languages or a CD with binary drivers). To install a new add-on, start YaST and select *Software › Add-On Products* . You can select various types of product media, like *CD, FTP, USB* mass storage devices (such as *USB* flash drives or disks) or a local directory. You can work also directly with *ISO* files. To add an add-on as ISO file media, select *Local ISO Image* then enter the *Path* to *ISO Image*. The *Repository Name* is arbitrary.

####1 Add-Ons

To install a new add-on, proceed as follows:

1.	In *YaST* select *Software › Add-On Products* to see an overview of already installed add-on products.

2.	To install a new add-on product, click *Add*.

3.	From the list of available Media Types specify the type matching your repository.

4.	To add a repository from a removable medium, choose the relevant option and insert the medium or connect the *USB* device to the machine, respectively.

5.	You can choose to *Download Repository Description Files* now. If the option is unchecked, YaST will automatically download the files later, if needed. Click *Next* to proceed.

6.	When adding a repository from the network, enter the data you are prompted for. Continue with *Next*.

7.	Depending on the repository you have added, you may be asked if you want to import the *GPG* key with which it is signed or asked to agree to a license.

    After confirming these messages, YaST will download and parse the metadata and add the repository to the list of *Configured Repositories.*.

8.	If needed, adjust the repository *Properties* as described in “*Managing Repository Properties*” or confirm your changes with *OK* to close the configuration dialog.

9.	After having successfully added the repository for the add-on media, the software manager starts and you can install packages. Refer to *Installing* or *Removing Software* for details.

####2 Binary Drivers

Some hardware needs binary-only drivers to function properly. If you have such hardware, refer to the release notes for more information about availability of binary drivers for your system. To read the release notes, open *YaST* and select *Miscellaneous › Release Notes*.

