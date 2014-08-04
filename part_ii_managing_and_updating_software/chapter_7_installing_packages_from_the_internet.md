## Installing Packages From the Internet

By default, it is only possible to install packages from configured and enabled repositories. Apart from the official repositories that are configured during the installation, numerous other repositories exist. The openSUSE® Build Service hosts several hundred ones and a lot of third party repositories exist, too—see http://en.opensuse.org/Additional_package_repositories.

openSUSE offers two easy ways to install from these repositories *without* the need to first subscribe to them. The *1-Click Install* method allows you to install packages directly from a *Web* browser, while the *YaST Package Search* lets you query almost all known repositories for openSUSE. You can directly install any package found by the package search module.

>**Warning: Trusting External Software Sources :**
Before installing from any external software repository, make sure it can be trusted. openSUSE is not responsible for any potential problems arising from software installed from third-party software repositories.

####1 One Click Install

Installation using *1-Click Install* is available from a lot of repositories available on Web interfaces. A very popular interface is the openSUSE *Build* Service software search.

**Procedure 7.1: Installing Packages from the openSUSE Build Service via 1-Click Install **

1.	Start the openSUSE Build Service search interface at http://software.opensuse.org/search.

2.	Select your system version from the drop-down menu, for example openSUSE 12.3.

3.	Enter the name of the package you want to install, for example the *OpenStreetMap* editor josm.

4.	To refine the search, adjust the *Search Options* according to your *wishes*.

5.	Click* Search*.

6.	From the results list select the preferred item by clicking its *1-Click Install* button.

7.	In the Web browser's download dialog, select to open the file with the *YaST Meta Package Handler*.

    The 1-click installer opens the *Additional Software Repositories* dialog. It shows the repositories providing the packages you want to install per *1-Click Install*. They are activated per default. To proceed with the installation, keep the repository selection. By default, you remain subscribed to these repositories after the installation has finished and you will receive updates from them in the future.

8.	If you want to use the new repositories only once instead, uncheck *Remain Subscribed* to *These Repositories* after *Installation*. Click *Next* to proceed.

9.	Now select the software packages that should be installed. Normally there is no need to change the default selection. Click *Next* to proceed.

10.	The Proposal screen summarizes the choices you made. Click *Customize* to restart the configuration steps from above. Click *Next* and *Yes* to proceed with the installation.

11.	Enter the root password to start the installation. In case a new repository has been added you also need to confirm the import of the repository's *GPG* key. During the installation several progress pop-ups appear that do not need any interaction. After reading the “*Installation was successful*” message, click *Finish*.

>**Tip: Disabling 1-Click Install Feature :**
If you want to disable the 1-Click install feature, uninstall the yast2-metapackage-handler package using YaST. Alternatively, enter the following command as root:

    rpm -e yast2-metapackage-handler
