<a name="readme-top"></a>

# RS-Components
## AddToCart

### RS-Components/script/

* [RS_AddToCart_v01.jmx](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/script/RS_AddToCart_v01.jmx) - JMeter script that goes on the following user journey
  - Homepage->Category Page 1->Category Page 2->Category Page 3->Product Page->Basket Page
* Has Ultimate thread group with 5 ramp ups each for 2 Mins
* Contains samplers like 
````
  * Response Time Graph
  * Transactions per Second
  * Summary Report
  * View Results Tree
  * Hits per Second
  * Active Threads Over Time
  * Final Stage 5 - Throughput 
  * Aggregate Report   
````

### RS-Components/artifacts/

* CSV Data [CSV Data set Config](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/artifacts/Categories.csv) to be used 
* Extract the .zip [RSTestResults.zip](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/artifacts/RSTestResults.zip) for the TestResults.xml & update the xml path in View Results Tree listener
* Test Results .jtl [RSTestResults.jtl](https://github.com/pragatheboss/RS-Components/blob/2ac1ed40b4c9d92e58e804d62b0523b81b810760/artifacts/RSTestResults.jtl) update the .jtl path / browse the .jtl path in all the listeners except View Results Tree . Apply the regular expression extractor (RS_AddToCart.*) if required for filtering only the parent samples
* Extract the .zip [RSTestResults.html.zip](https://github.com/pragatheboss/RS-Components/blob/2ac1ed40b4c9d92e58e804d62b0523b81b810760/artifacts/RSTestResults.html.zip) for JMeter HTML report that contains APDEX , Statistics , Charts and other metrics
* Document [RS_AddToCart_Doc_v01.docx](https://github.com/pragatheboss/RS-Components/blob/2ac1ed40b4c9d92e58e804d62b0523b81b810760/artifacts/RS_AddToCart_Doc_v01.docx) that will give entire picture of the test scripting,observations,strategy,errors,Reports etc..


> **Note**
> Please go through the document [RS_AddToCart_Doc_v01.docx](https://github.com/pragatheboss/RS-Components/blob/2ac1ed40b4c9d92e58e804d62b0523b81b810760/artifacts/RS_AddToCart_Doc_v01.docx) to get an overall idea of the testing strategy

### RS-Components/images/

* Contains images and snapshots of the executed test
  - [Response Time](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/images/Response%20Time.png)
  - [Stage 5 Throughput](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/images/Stage%205%20Throughput.png)
  - [Summary Report.png](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/images/Summary%20Report.png)
  - [Transactions Per Second.png](https://github.com/pragatheboss/RS-Components/blob/bfcca6144fa434358e5eac0cecb190b92fc2b367/images/Transactions%20Per%20Second.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



