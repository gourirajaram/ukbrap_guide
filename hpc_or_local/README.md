Shell scripts to install and use [`dxtoolkit`](https://documentation.dnanexus.com/user/helpstrings-of-sdk-command-line-utilities) commands through your local terminal/ HPC <br>
- After `installation.sh`, to login again run <br>
<pre>module load miniconda3/4.5.1
dx login </pre> <br>
- To run a bash script through your command terminal/locally , login using dx login and run ` bash scriptname.sh`. This submits a job on the RAP cluster. Refer to `ukbrap_bashscript_structure.png` for a general structure of bash script <br>
- `filetransfers` - to download from and upload files into the dnanexus project directory <br>
- `ukbrap_bashscript_structure.png` - structure of a bash script to run RAP tools through your HPC/local system. Refer [here](https://github.com/mostafavilab/burden_test_regenie/blob/main/wes_rare_variant_pcs/estimate_fine_structure_PCs.sh) to copy the script <br> 
