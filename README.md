# DataLoader-for-MachineLearning-Frameworks
Easily load image data for training NN

## Import DataLoader

```python
from dataloader import DataLoader
```

## Usage

```python
DIR = "my_dataset/EyeImages"
CATEGORIES = ["closedLeftEyes","closedRightEyes","openLeftEyes","openRightEyes"]

my_data = DataLoader(DIR,CATEGORIES)

X_train, X_test, y_train, y_test = my_data.create_data(cmap='rgb',test_size=0.2,random_state=42,normalize=True)
```

Link to [database used](https://github.com/rumeetsingh/my_dataset) above.

Follow Code in [example.ipynb](https://github.com/rumeetsingh/DataLoader-for-MachineLearning-Frameworks/blob/master/example.ipynb) for implementation.

### Made with ❤️ by Rumeet Singh ###
