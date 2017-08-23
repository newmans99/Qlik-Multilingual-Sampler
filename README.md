# Qlik-Multilingual-Sampler
A Qlik Sense sampler application demonstrating multiple techniques to support your multilingual, multitenant, and multi-departmental string requirements.

**NOTE**: This sampler application requires Qlik Sense Sept/2017 release. The Technical Preview is currently available for existing partners and customers here: [Qlik Communities: Qlik Sense September 2017 Technical Preview](https://community.qlik.com/blogs/technicalbulletin/2017/08/22/qlik-sense-september-2017-technical-preview-is-now-available)

## Description
Description coming soon.

### <a name="simple"></a>Implementation - Simple : Exploration Only
These steps will get you started quickly to explore the Multilingual Sampler application. After implementing this, you may want to consider implementing the secured version (see steps below).

#### Requirements
* Qlik Sense Server (or Desktop) Sept/2017 Release or higher.
* Access to QMC, to upload helper widgets and modify connection string.

#### Steps
1. Download the [Sampler Repository ZIP file](https://github.com/newmans99/Qlik-Multilingual-Sampler/archive/master.zip)
2. Unzip the contents to a directory accessible to QMC or Desktop.
3. Import Qlik Sense application
  1. For Qlik Sense Server
    1. From QMC: Apps -> Import - "**[UnzipPath]\app\Multilingual & Multi Tenant-Department Sampler.qvf**"
    2. From QMC: Extensions -> Import - "**[UnzipPath]\app\LanguageHelperWidgets.zip**"
    3. From Hub: Open the "**Multilingual & Multi Tenant-Department Sampler**" application from "My Work".
    4. From App Overview: Open the "**Introduction**" Story to explore and learn about the application.
  2. For Qlik Sense Desktop (coming soon)


### <a name="moderate"></a>Implementation - Moderate : Simple + Updating
These steps build on the previous "Basic" steps to enable the developer to reload the data and make modifications to the string definitions.
**NOTE:** This section has not been completed yet.

#### Requirements
* Complete [Simple Implementation Steps](#simple)

#### Steps
1. For Qlik Sense Server:
  1. Update connection string (coming soon)
  2. Test Updating
2. For Qlik Sense Desktop (coming soon)

### <a name="advanced"></a>Implementation - Advanced : Moderate + Security Enabled
These steps build on the previous "Moderate" steps to enable the administer to test logging in as different users to see the impacts to string and data definitions in the Sampler Application. **NOTE:** This section has not been completed yet.

#### Requirements
* Complete [Moderate Implementation Steps](#moderate)
* Requires Qlik Sense Server, Desktop does not support Section Access (security).

#### Steps
1. Add users to authentication system
2. Setup UDC connection
3. Enable security in QVS file
4. Reload application
5. Publish application
6. Test application



### Troubleshooting
Here is where I will put common problems that people have encountered. If you do not see your problem, please raise an [Issue](https://github.com/newmans99/Qlik-Multilingual-Sampler/issues) and I will attempt to respond as quickly as I can.

* None known at this time.

## Enhancements
There are a number of enhancements that I would like to make to this application, please feel free to fork and submit a merge request for any enhancements to this project. For a list requested enhancements, please see [Issue](https://github.com/newmans99/Qlik-Multilingual-Sampler/issues).
