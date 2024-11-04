# Project_3-API-perfomance-tests-with-JMeter

This project aims to check the performance of individual [Restful-Booker](https://restful-booker.herokuapp.com/) endopoints according to [API documentation](https://restful-booker.herokuapp.com/apidoc/index.html)

The tests were carried out in 3 different iterations differing in the number of users:
- 1 user per 10s
  - [Summary raport](https://github.com/sehsune/Project_3-API-perfomance-tests-with-JMeter/blob/main/summary_1.csv)
- 10 users per 10s
  - [Summary raport](https://github.com/sehsune/Project_3-API-perfomance-tests-with-JMeter/blob/main/summary_10.csv)
- 100 users per 10s
  - [Summary raport](https://github.com/sehsune/Project_3-API-perfomance-tests-with-JMeter/blob/main/summary_100.csv)
- 1000 users per 10s
  - [Summary raport](https://github.com/sehsune/Project_3-API-perfomance-tests-with-JMeter/blob/main/summary_1000.csv)
  
Tests were performed using the JMeter tool

**How to run tests**

 Clone repository :
 ``` git clone https://github.com/sehsune/Project_3-API-perfomance-tests-with-JMeter.git  ```

- Install  JMeter from https://jmeter.apache.org/download_jmeter.cgi
- Open JMeter
- File > Open > Restful-booker perfomance test.jmx
- Run the test plan by clicking on the "Start" button

