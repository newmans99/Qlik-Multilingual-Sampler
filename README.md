# Qlik-Multilingual-Sampler
A Qlik Sense sampler application demonstrating multiple techniques to support your multilingual, multitenant, and multi-departmental string requirements.

**NOTE**: This sampler application requires Qlik Sense Sept/2017 release. The Technical Preview is currently available for existing partners and customers here: [Qlik Communities: Qlik Sense September 2017 Technical Preview](https://community.qlik.com/blogs/technicalbulletin/2017/08/22/qlik-sense-september-2017-technical-preview-is-now-available)

## Description
Description coming soon.

### <a name="simple"></a>Implementation: Simple - Explore the Application
These steps will get you started quickly to explore the Multilingual Sampler application. After implementing this, you may want to consider implementing the secured version (see steps below).

#### Requirements
* Qlik Sense Server (or Desktop) Sept/2017 Release or higher.
* Access to QMC, to upload helper widgets and modify connection string.

#### Steps
<ol>
<li>Download the [Sampler Repository ZIP file](https://github.com/newmans99/Qlik-Multilingual-Sampler/archive/master.zip)
<li>Unzip the contents to a directory accessible to QMC or Desktop.
<li>Import Qlik Sense application & widget from zip file
<br>For Qlik Sense Server:
  <ol>
    <li>From QMC: Apps -> Import - "Your_Unzip_Path\app\Multilingual & Multi Tenant-Department Sampler.qvf"
    <li>From QMC: Extensions -> Import - "Your_Unzip_Path\app\LanguageHelperWidgets.zip"    
  </ol>
<br>For Qlik Sense Desktop
  <ol>
  <li>(Coming soon)
  </ol>
  <br>
<li>Open the **"Multilingual & Multi Tenant-Department Sampler"** application from "Hub -> My Work".
<li>From the Application Overview: Open the **"Introduction"** Story to explore and learn about the application.
</ol>

### <a name="moderate"></a>Implementation: Moderate - Simple + Updating Strings
These steps build on the previous "Basic" steps to enable the developer to reload the data and make modifications to the string definitions.
**NOTE:** This section has not been completed yet.

#### Requirements
* Complete [Simple Implementation Steps](#simple)

#### Steps
For Qlik Sense Server:
<ol>
<li>Update connection string (coming soon)
</ol>
For Qlik Sense Desktop (coming soon)
<ol>
</ol>

### <a name="advanced"></a>Implementation: Advanced - Moderate + Security Enabled
These steps build on the previous "Moderate" steps to enable the administer to test logging in as different users to see the impacts to string and data definitions in the Sampler Application. **NOTE:** This section has not been completed yet.

#### Requirements
* Complete [Moderate Implementation Steps](#moderate)
* Requires Qlik Sense Server, Desktop does not support Section Access (security).

#### Steps
<ol>
<li>Add users to authentication system
<li>Setup UDC connection
<li>Enable security in QVS file
<li>Reload application
<li>Publish application
<li>Test application
</ol>


### Troubleshooting
Common problems and resolutions that others have encountered. If you do not see your problem, please raise an [Issue](https://github.com/newmans99/Qlik-Multilingual-Sampler/issues) and I will attempt to respond as quickly as I can.

* None known at this time.

## Enhancements
There are a number of enhancements that I would like to make to this application, please feel free to fork and submit a merge request for any enhancements to this project. For a list requested enhancements, please see [Issue](https://github.com/newmans99/Qlik-Multilingual-Sampler/issues).
