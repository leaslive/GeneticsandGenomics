DATA SETUP INSTRUCTIONS

The dataset for this project is not included in the GitHub repository. 
Each team member must download the data files manually and place them in the correct location before running the notebook.
Download the following two files from Moodle:

genotypes.vcf
annotations.txt

In the project’s root directory (the directory that contains analysis.ipynb), create a new folder named data.
The directory structure should look like this:

project_root/
analysis.ipynb
data/
README.md
.gitignore

Move the downloaded data files into the newly created data/ folder. After this step, the folder should look like:

data/
genotypes.vcf
annotations.txt

Do not rename these files. The notebook expects these exact filenames.

Open the project in VS Code, open analysis.ipynb, and run all cells. The notebook loads the data from the following paths:

DATA_DIR = "data"
vcf_path = DATA_DIR + "/genotypes.vcf"
ann_path = DATA_DIR + "/annotations.txt"

The data folder is intentionally excluded from GitHub using .gitignore, because the files (especially the VCF) are large. Each collaborator must download and place the files locally.
