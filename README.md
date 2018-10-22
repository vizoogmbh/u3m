
![U3M Logo](http://u3m.info/_src/logo_small.png)

# U3M
Unified 3D Material

Thank you for coming to the Github Page of U3M and working with us on it during these early stages!

Right now, different vendors output their digital materials either in a proprietary format or embedded directly in their styles. And while various integrations already exist, there is a steady conversion that has to take place, different file types to manage and still a lot of incompatibility. Therefore, the Unified 3D Material is being developed as a bridge between software vendors in the Apparel industry with the goal to replace proprietary material formats with a single open–source format.

Split into three parts, the U3M format manages to be flexible enough to embrace new input as well as manage your personal company data, yet structured enough to provide a reliable visualization. For a more detailed overview, take a look at the Unified3DMaterial Documentation on here. 

If you want to have a conversation, discuss changes, give feedback, simply add an Issue to the Github page

### Schema
Part 1 of u3m is the version number of the file format. Always make sure it matches the corresponding U3M-schema. This will improve compatibility, and later allow for backward compatibility as well. 

### Material
The material section is the core of the U3M. It contains meta data, visual data for front and back, and hopefully soon physical, supplier and construction data as well. It comes with a predefined and standardized structure and data-types, so every party reading & writing the format can rely on it. This will enable and improve the interoperability between applpications.

### Custom
The custom section is the dynamic framework that makes interoperability possible. It enables every technology vendor to add the proprietary data they specifically require to read & write the files, as well as providing brands and suppliers a place to store production or workflow information. 
There is no predefined schema for this part, therefore it has to be read & written as it is, without any changes. The exception is your own, proprietary custom section. 

## Examples

A few examples of u3m files with textures: 
https://vizoo.sharepoint.com/:f:/g/Eq9UaYaqWehEsNduuTsHgvQBufLeRpYzIXERsWXwLXWEOQ?e=22AcNI

## License

GNU General Public License v3.0 

