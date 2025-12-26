## Using pipenv for environemnt isolation in pyhton development

[Doucmentation is the best!!](https://pipenv.pypa.io/en/latest/)

- collaboration work တွေအတွက်ဆိုရင် pipenv က အသုံးသင့်ဆုံးပဲ ။
- pip+venv ထက်လည်းပိုကောင်းတယ်ပေါ့နော် ။
- lock file ပါတယ်။ Dependency resolution ပိုကောင်းတယ် ။
- Legacy ကဒီလို ဆိုပေမယ့် no longer recommended ပါ။<br>
`pip install --user pipenv`

- ဒီထဲက flow ကတော့ python runtime ကို anaconda က ယူပြီး library ကို pipenv ကနေ install မှာပါ။
  
### version စစ်ရန်
`python3 --version`<br>
`pip3 --version`

### create conda environment, activate it and install python
`conda create --name my_conda_env python=version_needed`
<br>
`conda activate my_conda_env`
<br>
`pipenv install --python <python_path_from_conda_env>`

- ပြီးလို့ version check လိုက်ရင် global က python မဟုတ်တော့ဘဲ conda env က python ဖြစ်နေပါပြီ ။

<img src="./pipenv_conda.png" width="300" height="300">

## **ML လုပ်ရင် conda မှာပဲ lib တွေကို env အလိုက် install ထားမှာဆိုတော့ ဒီလို practice ကို used to ဖြစ်သင့်ပါတယ် ။**
