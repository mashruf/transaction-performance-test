# transaction-performance-test

## Prerequisite
- Jmeter

## About this project:
Here we can login as admin, create user, agent and merchant. We can deposite money from system to agent and agent to customer. Customer can withraw money and make payment to merchant account. All these APIs were properly chained here with the help of Jmeter.

## How to run this project:
-You need to set path of java home and jmeter home in environment variables.
- clone this project
``` https://github.com/mashruf/transaction-performance-test ```
- In the source root project, give the following command:
``` jmeter -n -t transaction.jmx -l transaction.csv -e -o report ```
![screencapture-file-F-Sdet-Performance-testing-apache-jmeter-5-6-2-bin-transaction-performance-test-Reports-index-html-2023-12-30-02_13_19](https://github.com/mashruf/transaction-performance-test/assets/50927464/e436e741-0919-491b-82c5-28edc3a56f55)
