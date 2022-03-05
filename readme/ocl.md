## Domain 'ocl'
The **ocl** subfolder contains JSON file of OCL dictionary packages as .zip files to be imported. This is a possible example of its content:
```bash
ocl/
  └── test.zip
```
The JSON file inside .zip file loads all the concepts exported from OCL.
<br/>OCL package is a convenient way to load all the concepts to the dictionary.

#### Further examples:
Please look at the test configuration folder for sample import files for all domains, see [here](../api/src/test/resources/testAppDataDir/configuration).

OpenMRS RefApp 3.x Example [here](https://github.com/openmrs/openmrs-distro-referenceapplication/tree/3.x/package/config/configuration/ocl). 

## How to get a .zip of your concepts directly from OCL
If you have been using OCL to manage your dictionaries/collections, it's easy to grab a .zip from the OCL online app directly. Steps: 
1. Go to https://app.openconceptlab.org/
2. Go to the collection you are looking for 
3. Click the "Versions" tab
4. Find the latest released version of the collection you would like to use
5. Click the download icon for that version, and select the option "Export Version". This will automatically download a .zip for that collection. <img width="250" alt="image" src="https://user-images.githubusercontent.com/67400059/156861305-7eee2469-ea44-464f-8bd5-3e6ecb3db2ba.png">

