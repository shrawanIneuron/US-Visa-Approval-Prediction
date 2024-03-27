# US-Visa-Approval-Prediction

## Live material docs
[Link](https://docs.google.com/document/d/1UFiHnyKRqgx8Lodsvdzu58LbVjdWHNf-uab2WmhE0A4/edit)

## Git commands
```bash
git add .

git commit -m "Updated"

git push origin main


```
## How to run?
```bash
conda create -n visa python=3.8 -y
```

```bash
 conda activate visa
```


```bash
pip install -r requirements.txt
```

# workflow
1.constant      # important variables

2.config_entity # All the folders and file paths

3.artifact_entity # Output from the component

4.component # actual stage

5.pipeline #Which stage runs first

6.app.py / demo.py

### Export the environment variables
```bash

export MONGODB_URL="mongodb+srv://<username>:<password>...."

export AWS_ACCESS_KEY_ID=<AWS_ACCESS_KEY_ID>

export AWS_SECRET_ACCESS_KEY=<AWS_SECRET_ACCESS_KEY>
```