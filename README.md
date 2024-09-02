# MaterialsMine_YAMLconvert

## Project Overview
This project contains two Python scripts designed for converting between XML and YAML file formats. These scripts are particularly useful for handling structured data in the field of materials science, allowing easy conversion of data from XML to YAML format and vice versa.

**Production MM web:** https://materialsmine.org/nm/

**Web project:** https://github.com/Duke-MatSci/materialsmine

**XSD Schema:** https://qa.materialsmine.org/portal/view-schema

**API Docs:** https://materialsmine.org/api/api-docs/

## File Descriptions
### 1. XML_to_YAML.ipynb
#### Functionality
This script is used to convert an XML file into a YAML file. It parses the structured data from an XML file into a dictionary and then writes it into a YAML file.

#### How to Use
- File Path Setup: In the script, modify the following variables to point to your input XML file path and output YAML file path.
  - xml_input_path: The path to the input XML file.
  - yaml_output_path: The path where the generated YAML file will be saved.
- Run the Script: Execute the script, and the YAML file will be generated at the specified location.

### 2. YAML_to_XML.ipynb
#### Functionality
This script converts a YAML file back into an XML file. It loads data from a YAML file and converts it into its original XML structure.

#### How to Use
- File Path Setup: In the script, modify the following variables to point to your input YAML file path and output XML file path.
  - yaml_input_path: The path to the input YAML file.
  - xml_output_path: The path where the generated XML file will be saved.
- Run the Script: Execute the script, and the XML file will be generated at the specified location.

## Usage Notes
- These scripts assume that the input XML and YAML files are well-formed and adhere to the expected structure. Please ensure the file formats are correct to avoid errors during the conversion process.
- If you encounter errors during conversion, review the structure of your files to ensure that element names are valid and conform to XML standards.

## Contributions
If you have any questions or suggestions, feel free to submit an issue or pull request. Thank you for using and supporting this project!




