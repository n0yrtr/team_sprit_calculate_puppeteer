## pyenv + pyenv-virtualenv
 pyenv は python 自体のインストール管理
 3.11.1が最新でまだなかったのでinstall

`pyenv install 3.11.1`
 
上記でinstallしたpythonをプロジェクト専用のpython として作成する。
`pyenv virtualenv 3.11.1 team_sprit_calculate_puppeteer`

`pyenv versions`
```  system
  3.6.5
  3.7.0/envs/toggle_report
  3.8.6
  3.8.6/envs/repository_gen
  3.8.6/envs/team_mvp
  3.8.6/envs/teammvp
  3.11.1
  3.11.1/envs/team_sprit_calculate_puppeteer
  alexa_skill_holiday_ps4
  repository_gen
  teammvp
  team_mvp
  team_sprit_calculate_puppeteer
  toggle_report
```

今いるフォルダで使用するpythonを指定
`pyenv local team_sprit_calculate_puppeteer`

## pip
pip install pyppeteer
