## Data Source

Retinopathy image dataset is downloaded from kaggle.com.
- Dataset       : [APTOS 2019 Blindness Detection](https://www.kaggle.com/competitions/aptos2019-blindness-detection/data). The APTOS dataset is used in Alsuwat et al., 2022 and has high rating in Kaggle.
- Size          : 9.51G 
- Num of images :  
- Image format  : JPEG 

## Download data source

Retina fundus mages are downloaded using [Kaggle API](https://github.com/Kaggle/kaggle-api/blob/main/docs/README.md)

0. Prerequisite: must have python3 installed
1. Install kaggle-api: run `pipx install kaggle` in CLI (Ubuntu in WSL2)
2. Get kaggle API credential: Log into kaggle and go to 'Account' tab under 'Settings'. Select 'Create New Token' under 'API'
3. Download dataset: `kaggle competitions download -c aptos2019-blindness-detection`

## Preliminary dataset evaluation
