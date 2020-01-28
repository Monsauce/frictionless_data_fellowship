## Creating my first data package
### Introduction 
Data packages is a tool created by the [Open Knowledge Foundation][link_OKF] to be able to bundle your raw data and your meta-data so that it becomes more usable and shareable. 

For my first data package I will use data from my [paper][link_paper] in Freshwater Biology on variation in benthic algal growth rate in experimental mesocosms with native and non-native omnivores. I will use the [Data Package Creator][link_DPC] online tool for this package creation. The second package will be done in the R programming language. 

Presently, the data is distributed in my GitHub repo but the Data Package Creator will allow me to combine the algae, snail and tile sampling data together in one place. 

### Write a Table Schema
A schema is a blueprint that tells us how your data is structured, and what type of content is to be expected in it. I will start by loading the algae data. The [data][link_data] is already available on GitHub so I will use the hyperlink option in the Data Package Creator. To create the schema, I have to load my data using the **Raw** link from GitHub. Since my data has the first row as the column headings the Data Package Creator recognizes them. Once loaded, I can add addition information about my different variables in the "Title" and "Description." For example, for the variable "Day" I added a more explicit description in the of "Experimental day" in the Title and more information about the length of the experiment in the Description. 

To add the snail and tile sampling datasets I will click on "Add a resource" for each and add the titles and descriptions. 

### Add dataset's metadata
Next I will add the data's metadata. I added a title, author and description to the metadata and I choose tabular data package since its just CSV files. I also added a CC-BY license so that anyone can use the data as well. 

Then I validated the data (see note below) and downloaded the package which is available [here][link_firstdatapackage].


*Note: make sure not to use any uppercase letters or dashes in your package name or the resource names or package will not be validated*





[link_OKF]: https://okfn.org/
[link_paper]:https://onlinelibrary.wiley.com/doi/full/10.1111/fwb.13378
[link_data]:https://github.com/Monsauce/Origin-omnivory-and-stability/blob/master/Algae.csv
[link_DPC]:http://create.frictionlessdata.io/
[link_firstdatapackage]:https://github.com/Monsauce/frictionless_data_fellowship/blob/master/firstdatapackage.json
