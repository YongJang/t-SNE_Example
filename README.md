# t-SNE Example Code.
t-SNE Example code which uses students' answers data.
This code omits a process of making term-doc matrix (downloads the preprocessed data directly).
Each of the data file contains term-doc matrix extracted from one of 31 questions (written in Korean).

# Dependencies
```bash
conda create -n [env_name] -y python=3.6
source activate [env_name]
pip install requirement.txt -r
cd ./data
bash download_data.sh
```

