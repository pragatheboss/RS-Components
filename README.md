# RS-Components

### RS-Components/script/
* [RS_AddToCart_v01.jmx](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/script/RS_AddToCart_v01.jmx) - JMeter script that goes on the following user journey
  - Homepage->Category Page 1->Category Page 2->Category Page 3->Product Page->Basket Page
* Has Ultimate thread group with 5 ramp ups each for 2 Mins
* Contains samplers like 
  - Response Time Graph
  - Transactions per Second
  - Summary Report
  - View Results Tree
  - Hits per Second
  - Active Threads Over Time
  - Final Stage 5 - Throughput 
  - Aggregate Report 


### RS-Components/artifacts/

* CSV Data to be used - [CSV Data set Config](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/artifacts/Categories.csv)
* Extract the zip [RSTestResults.zip](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/artifacts/RSTestResults.zip) & update the xml path in View Results Tree listener



### RS-Components/images/
* Contains images and snapshots of the executed test
  - [Response Time](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/images/Response%20Time.png)
  - [Stage 5 Throughput](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/images/Stage%205%20Throughput.png)
  - [Summary Report.png](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/images/Summary%20Report.png)
  - [Transactions Per Second.png](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/images/Transactions%20Per%20Second.png)





