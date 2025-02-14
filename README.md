# 可以把交易列表用email发送出来
通过修改yaml文件可以实现将选定时间段的交易列表通过邮箱的形式发送，目前暂未写完，预计一个月能把功能完善，改编自@David Schlachter

# Send Transaction List via Email
By modifying the YAML file, you can send the transaction list for a selected time period via email. Currently, it is not yet completed and is expected to be fully functional within a month. Adapted from @David Schlachter.

# Summary emails for Firefly III

Background: Self-hosted budgeting software [firefly-iii](https://github.com/firefly-iii/firefly-iii) doesn’t have an email reports feature. I missed this when I switched from Mint.

Objective: send a monthly summary email, showing totals for each category.

Usage: run 'monthly-report.py' on the command line (e.g. with cron) to send the category report for the previous month. Add your configuration data to config.yaml (copy from config.yaml.sample).

Known issues:

- Only supports a single currency

Installation:

Install the dependencies from `requirements.txt`. 

```
pip install -r requirements.txt
```

Screenshot:

![Firefly-iii monthly report screenshot](screenshot.png?raw=true)


