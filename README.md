# 一畝三分地自動登入 1point3acres_AutoLogin

```
[2017.11.13 update]
If your chrome will automatically open a setting page, please update your Chrome driver
```
### Installation

1. Install [Selenium](https://pypi.python.org/pypi/selenium) 
```
$ pip install -U selenium
```

2. Download [Chrome driver](https://sites.google.com/a/chromium.org/chromedriver/)

3. Edit Chrome driver path, Username, Password in 1point3acres_auto.py
```
chrome_path = 'YOUR__CHROME__DRIVER__PATH'
browser.find_element_by_id("ls_username").send_keys("YOUR__1point3acres__USERNAME")
browser.find_element_by_id("ls_password").send_keys("YOUR__1point3acres__PASSWORD")
```

4. Set crontab 

Edit all crontab commands
```
$ crontab -e 
```

command will be executed everyday at 00:00 AM
```
$ @daily python YOUR__1point3acres_auto.py__PATH  
```

or setting on specific time e.g. 9:30 AM
```
$ 30 9 * * * python YOUR__1point3acres_auto.py__PATH  
```

some daily login answers
testing google crawler lol

【题目】 下面哪个州，对公司友好，所以吸引了美国很多公司注册？
特拉华州(Delaware, a small state in northeast, one of the thirteen states in American Revolution)

【题目】 下面哪个州，有state income tax
Mississipi
Idaho
Hawaii
Georgia


【题目】 下面哪个州，没有state income tax
Alaska
Washington
Tennessee
Florida

【题目】 一亩三分地是哪年创立的？
2009
