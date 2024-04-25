# Managing your files with R projects
R Projects are a great way to keep your files and data associated with any project in one tidy place. An R Project is nothing more than a fancy folder which represents the entire world for all the files in the project. This means that all file paths are relative to the structure of the project - you do not need to locate the precise file path for your data file or your r code, etc. 

If you tend to keep all of your data in one folder on you computer, and all of your r files in another folder, you've probably experienced the pain of having to manually type the file path in your r code (e.g., `dat <- read_csv('~/Users/MyComputer/Dropbox/R_data/Dissertation/Study1/raw_data.csv`)

R Projects are also good for reproducibility and sharing. This is because you can share an R project and all of its files with someone else (or on another computer) and run it somewhere else (assuming R and all the libraries are installed!). Moreover, the use of relative file paths in the project means that you don't need to worry renaming or rewriting your file paths on a new computer. An R Project is basically a one-stop shop for *all* of the files associated with a project, no matter how large or small.

An R project can be associated with an existing folder, or you can make a new folder. You can host that folder anywhere on your computer, including within folders you sync using a cloud storage provider (e.g., Dropbox, Google Drive, Microsoft OneDrive), or you could use a version control platform such as GitHub. 

Be careful using cloud service providers like OneDrive because these providers like to host all of your files in the cloud and *not* on your computer. If this happens, the actual file paths of your files are all converted to relate to the cloud storage provider and are then downloaded on demand as you need them. This can wreak havoc on an analysis where some but not all of the files are downloaded at any one time. Ensure your cloud provider settings allow you to store files physically on your computer, otherwise you may run into problems!


## Creating R Projects
Create new R Projects from within R Studio using the `File -> New Project` option in the main menu for R Studio. You can then choose a New Directory (i.e., create a new folder), Existing Directory (i.e., associate with an existing folder) or use Version Control (i.e., connect to a version control platform such as GitHub.). It is mainly up to you whether you would like to start fresh or use an existing folder. If you want to use version control, you will need to learn how to integrate R Studio with GitHub. 

## The R Project multiverse
You can have more than one R Project open at a time. If you do this, you'll notice that each project opens up its own instance of R Studio. These run independently from one another, so you could in theory work on two or more projects at once. 