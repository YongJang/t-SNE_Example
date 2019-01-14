# t-SNE Example Code.
t-SNE Example code which uses students' answers data.<br>
This code omits a process of making term-doc matrices (downloads the preprocessed data directly).<br>
Each of the data file contains the term-doc matrix extracted from one of 31 questions (written in Korean).<br>
<br>
![Example](https://github.com/YongJang/t-SNE_Example/blob/master/example.png?raw=true)
<br>
# Dependencies
```bash
conda create -n [env_name] -y python=3.6
source activate [env_name]
pip install -r requirement.txt
cd ./data
bash download_data.sh
```

