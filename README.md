# Qlik-Multilingual-Sampler
A Qlik Sense sampler application demonstrating multiple techniques to support your multilingual, multitenant, and multi-departmental string requirements.

**NOTE**: This sampler application requires the Qlik Sense Sept/2017 release. The Technical Preview is currently available for existing partners and customers here: [Qlik Communities: Qlik Sense September 2017 Technical Preview](https://community.qlik.com/blogs/technicalbulletin/2017/08/22/qlik-sense-september-2017-technical-preview-is-now-available)

## Description
Description coming soon.

### <a name="simple"></a>Basic Implementation - Ability to explore the application
These steps will get you started quickly to explore the Multilingual Sampler application. After implementing the basic steps, you may want to consider implementing the complete version so that you can update/modify the strings and/or use the test users for testing user language preference settings.

These steps will get you started quickly to explore the Multilingual Sampler application. After implementing this, you may want to consider implementing the [Advanced Installation](./wiki/Full-Implementation#advanced-installation) so that you can update/modify the strings and/or use the test users for testing user language preference settings.

#### Requirements
* Qlik Sense Server (or Desktop) Sept/2017 Release or higher.
* Access to QMC, to upload helper widgets and modify connection string.

#### Steps
1. Download the [Sampler Repository ZIP file](https://github.com/newmans99/Qlik-Multilingual-Sampler/archive/master.zip)
2. Unzip the contents to a directory accessible to QMC or Desktop.
3. Import Qlik Sense application & widget from zip file using one of the methods below.

**Method 1: Qlik Sense Server -**
1. From QMC: Apps -> Import - "Your_Unzip_Path\app\Multilingual & Multi Tenant-Department Sampler.qvf"
2. From QMC: Extensions -> Import - "Your_Unzip_Path\app\LanguageHelperWidgets.zip"    

**Method 2: Qlik Sense Desktop -**
NOTE: You will not be able to implement the user language preferences testing steps using Qlik Sense Desktop.
1. (Coming soon)

After importing the applications and widgets...
1. Open the **"Multilingual & Multi Tenant-Department Sampler"** application from "Hub -> My Work".
2. From the Application Overview: Open the **"Introduction"** Story to explore and learn about the application.

### Next Steps
After explorering the Introduction Story, it is recommended that you complete the [Advanced Installation](./wiki/Full-Implementation#advanced-installation), which includes support for string updating and user language preference testing. 

### Contributing/Enhancements
There are a number of enhancements that can be made to this Sampler application, please feel free to fork this project and submit a pull request for any enhancements to this project. For a list of currently requested enhancements, please see the [Issue List](https://github.com/newmans99/Qlik-Multilingual-Sampler/issues).

Also, we are looking to get this Sampler translated to as many languages as possible. If you can translate the strings to any other language, please consider contributing to this project by following the instructions for [Adding More Languages to this Sampler](https://github.com/newmans99/Qlik-Multilingual-Sampler/wiki/How-to-add-more-languages-to-this-Sampler).

### Troubleshooting
Common problems and resolutions that others have encountered. If you do not see your problem, please raise an [Issue](https://github.com/newmans99/Qlik-Multilingual-Sampler/issues) and I will attempt to respond as quickly as I can.

* None known at this time.
