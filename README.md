# TERG
Toast Email Report Generator

Toast POS's back end is pretty rich in reporting tools, but sometimes you just want raw data, and you want that raw data emailed to you on a regular basis.
Toast's Data Export feature solves the first problem and this script solves the second.

This script does that. Given a working AWS CLI installation, Apache on Ubuntu, and a working Postfix setup,
it will probably be plug-and-play with your restaurant IDs.

#### Dependencies:
aws-cli, configured with the S3 credentials provided to you by Toast  
postfix with tested working SMTP settings  
mailutils  
zip  
apache  
bash  
