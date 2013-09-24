awsgo
=====
awsgo is a command line tool used to list and connect to linux ec2 instances.

Requirements
============
- ``python >= 2.7``(awscli require version >= 2.7)
- ``ruby >= 1.8``
- ``awscli >= 1.1.0``http://aws.amazon.com/cli

Installation
============
Step 1. Install Python

Step 2. Install awscli
```
pip install awscli
```
Step 3. Download awsgo

Step 4. Put key-pair under ``awsgo/etc/keys``

Usage
=====
***list region name:***
```
awsgo -q
```
***list all instances under default or specified region:***
```
awsgo -l [-r <region name>]
```
***login to an instance by id:***
```
awsgo -i <instance id> [-r <region name>]
```
***login to an instance by name:***
```
awsgo -n <instance id> [-r <region name>]
```
