## Do this now

- - Create a git repo `adv_mla_lab_3`
- create a new ds template using cookie cutter using `ccds`. Project name is `adv_mla_lab_3`
- Run 
```
git init
git remote add origin git@github.com:XXXXXXXXXXX (From github)
uv python pin 3.12.11  #(your python version)
uv add pandas==2.2.2 jupyterlab==4.6.1 scikit-learn==1.5.1
uv add mykrml_XXXXX --extra-index-url https://test.pypi.org/simple/ --index-strategy unsafe-best-match --active
```