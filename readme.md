# CitySchema: 
### Simple Repository/Catalog for Publishing, Extending and Preserving a Detailed, Living 3D City Model
The Bos3d Repository / Catalog is a self-contained archival information package that contains all of the data, metadata and finding aids that a user or automated program would need to discover, access and use any published component of the city-wide 3d model. 

The CitySchema Repository uses a system of tiled modules and simple arrangement of files to create a coherent referencing scheme for detailed terrain models, ground plan images and a collection of building, bridge and wall models -- which are each individually referenced.

Catalog data is provided in JSON and CSV format, systematically addresses each model.  This data is demonstrated with easy-to-use finder maps for tiled models and individual building models.  The same catalog files can be used by programmers to create new applications using city model components.   Each model resource is described with HTML metadata that is integrated with the catalog maps.  Each Building, Bridge and Wall model is delivered with a JSON file that describes its provenance, technical lifecycle and temporal status. 

This Repository Catalog addresses each of the requirements for the International Standards Organization Reference Model for an Open Archive Information System.  It may be used to assure the integrity of city-model assets for long-term preservation, and for the extension and improvement of the city model collection by a variety of users.

Deep down, the Repository / Catalog is a simple collection of HTML and data files.  These files link to each-other using relative path references, so that the entire repository catalog can be published on the web by simply dropping it into a web-accessible folder.  The repository catalog does not require any server-side processing, so that it renders exactly the same on an ordinary local file-system.  

This gitHub repository is does not include all of the data-files -- which would be too large to share via gitHub.  This repository can be cloned or downloaded to your file-system for making changes.    Thropught the magic of GitHub, youcan also explore the files here or render this very same collection of files in your browser.  For example uou might want to visit these pages:

## Explore This Repository as a Web Site!

Right-click these links to open in a new tab so that this window can stay in Git-hub.

* View the [Tiled Download Page](https://pbcgis.github.io/CitySchema-Bos3d-RepositoryCatalog/catalog/index.htm).  Click on tile I3 to try out how users can download assets, including individual building models. 
* Take a look at the [index to documentation](https://pbcgis.github.io/CitySchema-Bos3d-RepositoryCatalog/catalog/index.htm), which should be sufficient to explain how the city model is put together and how it can be used to coordinate activities across diverse tools and territories. 
* [Administration Guide](https://pbcgis.github.io/CitySchema-Bos3d-RepositoryCatalog/catalog/admin_readme.htm) describes the structure of the self-contained collection of HTML and CSS files that renders itself as the complete model repository catalog.
* [Style Guide and Page Template](https://pbcgis.github.io/CitySchema-Bos3d-RepositoryCatalog/catalog/template.htm) A page that concisely demonstrates the styling p0ssibilities afforded by the BOS3D.css stylesheet.  

Click the **Code** button to clone or download a zip of this archive.  Use your favorite text editor (I recommend the free Visual Studio Code application) to edit the files in the catalog folder.  Open the about.html page in your browser. Edit config.js to change something in the disclaimer or banner.  Observe how your saved changes are immediately reflected when you refresh the web page in your browser!  

To publish your collection on the web, simply copy the repository catalog to a directory that is accessible from your web server.  Your city model should be live!

## citySchema.org:
This repository is the Boston-Specific fork of from the  [citySchema.org](https://www.citySchema.org) project. 






