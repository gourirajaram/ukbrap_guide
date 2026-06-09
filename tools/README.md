Understanding and getting started with commonly used tools on UKB-RAP <br>
- `jupyterlab_ukb.pdf` - creating a jupyterlab environment <br>
- `ttyd.pdf` - opening the ttyd tool. It is a web-based terminal that offers basic shell access. However, note that it does not replicate a full login shell, so commands like `module load` or environment modules may not work as expected <br>
- `/ukbrap_guide/hpc_or_local` - submitting jobs through your local terminal. swiss-army-knife can be run using this <br><br>


## Note the following points before analysing files on RAP<br>
- ### File transfers <br>
- Files from your project directory have to be read/downloaded into your working compute environment to analyse them. Project directory files refers to files here ![Alt text](https://github.com/mostafavilab/ukbrap/blob/main/images/projectdir.png) <br> You can read them with the following file path <br> Example: `df=pd.read_csv("/mnt/project/test/data.csv")` where _test_ is a folder in your project directory. `/mnt/project/` is prefix to read files from project directory <br> The files can also be downloaded using file ID using [`dx download`](https://documentation.dnanexus.com/user/objects/uploading-and-downloading-files/small-sets-of-files/downloading-using-dx) . Example: `dx download file-J15Z4z0JVBykJqfQb8Pq64qy` <br> ![Alt text](https://github.com/mostafavilab/ukbrap/blob/main/images/fileID.png) <br>
- After analyses, files have to be uploaded into the project directory using [`dx upload`](https://documentation.dnanexus.com/user/objects/uploading-and-downloading-files/small-sets-of-files/uploading-using-dx) , otherwise the files are not saved. Example: `dx upload test.txt` <br>
- ### List of available instances. Refer [here](https://20779781.fs1.hubspotusercontent-na1.net/hubfs/20779781/Product%20Team%20Folder/Rate%20Cards/BiobankResearchAnalysisPlatform_Rate%20Card_Current.pdf) <br>
- ### Monitoring jobs <br>
To monitor jobs submitted/currently running using any availble tool refer : <br> 
![Alt text](https://github.com/mostafavilab/ukbrap/blob/main/images/monitor.png) 
 
