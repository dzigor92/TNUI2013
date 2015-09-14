### Broker ~ Processing of sequences.
------------------
In this task we will deal with the problem of processing sequential data. We Will obtain the historical data of stock exchange of different companies and we will analyse the value of his actions along the time. We Will define an algorithm that will allow us detect changes of behaviour, and finally, we will define a strategy of purchase/sell actions triggered when changes of behaviour has been detected.

The work consists of three parts.
  1. Implement an algorithm for sliding window (SLIDWIN).
  2. Implement an algorithm for adaptative window (ADWIN).
  3. Define an strategy for purchase/sale actions in order to obtain profits.

### ADWIN.
------------------
ADWIN is an adaptive sliding window algorithm for detecting change and keeping updated statistics from a data stream, and use it as a black-box in place or counters in learning and mining algorithms initially not designed for drifting data.
