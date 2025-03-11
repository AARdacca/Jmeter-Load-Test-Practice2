# JMeter Load Test


<h2>Project Summary:</h2> 
I conducted Load Testing and Stress Testing on the Booking APIs to evaluate their performance and identify system limits. Additionally, I implemented API Chaining (JMeter Collection) for the DMoney website’s Transaction APIs. For the Transaction APIs, data was retrieved from CSV files, and multiple API requests were executed concurrently using four threads in JMeter.

<h2>Test Case Scenarios for Load and Stress Testing:</h2>
Created a collection of APIs (JMeter Collection) consisting of Login API, Create Booking API, and Search API HTTP requests.
Executed Load Testing and Stress Testing to measure system performance and determine the bottleneck and capacity thresholds.<br>
<br>
Website for APIs - https://restful-booker.herokuapp.com

<h2>Testcase scenarios for API Chaining in Jmeter Test: </h2>
1. 5 agents perform deposits for 10 customers.<br>
2. 5 customers send money to another 10 customers.<br>
3. 5 customers make payments to 2 merchants.<br>
<br>
Website for APIs - http://dmoney.roadtocareer.net

<h2>How to Run?</h2>

<h3> Execute the following steps using JMeter: </h3> 
   
  - ``` git clone https://github.com/AARdacca/Jmeter-Load-Test-Practice1.git ```<br>
  - ``` Open ApacheJMeter ``` <br>
  - ``` From apacheJMeter open the JMX File ```<br> 
  - ``` Finally Run ```

<h3>Execute the following steps using CLI: </h3>

  - ``` git clone https://github.com/AARdacca/Jmeter-Load-Test-Practice1.git ```
  - ``` cd Jmeter-Load-Test-Practice1 ```
  - ``` jmeter -n -t './Booking API Load Test/booking.jmx' -l './Booking API Load Test/booking.jtl' -e -o Reports ``` 
  - ``` jmeter -n -t '../DMoney/DMoney.jmx' -l './DMoney/DMoney.jtl' -e -o Reports ``` 

<h2>Load and Stress Test Excel Report:</h2>

 - **[Load and Stress Test Report](https://docs.google.com/spreadsheets/d/1MH59oo19uTOWPBhVyRn9HDOqmdWgdIDo3_wzWawNNhw/edit?usp=sharing)**

<h3>Generated HTML report for Load Test</h3>

![1-Jmeter](https://github.com/user-attachments/assets/6070b371-077e-4455-9e64-8ac2413b2988)


<h3>Generated HTML report for Stress Test</h3>

![2-Jmeter](https://github.com/user-attachments/assets/4e886905-e2af-4a54-9be1-349055007b2c)


<h3>Generated HTML report for DMoney Jmeter Collection Test</h3>

![3-Jmeter](https://github.com/user-attachments/assets/0ab9a2ae-f2fd-49a9-a920-bcfac2b14d2c)

