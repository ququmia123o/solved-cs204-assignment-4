Download Link: https://assignmentchef.com/product/solved-cs204-assignment-4
<br>
5/5 - (1 vote)

<ol>

 <li>A group of N stations share a 56-kbps pure ALOHA channel. Each station outputs a 1000-bit frame on average once every 100 sec, even if the previous one has not yet been sent (e.g., the stations can buffer outgoing frames). What is the maximum value of N?</li>

 <li>Consider the delay of pure ALOHA versus slotted ALOHA at low load. Which one is less? Explain your answer.</li>

 <li>Performance of Slotted ALOHA:The efficiency of slotted ALOHA is Np(1-p)(N-1), where N is the number of active nodes, p is the probability that a node transmits in a given slot. Find the value of p that maximizes this expression. Using the value of p found earlier, find the efficiency of slotted ALOHA by letting N approach infinity.</li>

 <li>Show that the maximum efficiency of pure ALOHA is 1/(2e).</li>

 <li>Graph the efficiency of slotted ALOHA and pure ALOHA as a function of p for the followingvalues of N:a. N=15b. N=25c. N=35Write down your observations from the graph from all the values of N and for different values of ‘p’.</li>

 <li>Consider the binary exponential backoff algorithm, used in Ethernet CSMA/CD. When transmitting a frame that has already experienced n collisions, a node chooses the value of K at random from {0,1,2,…2n-1}. Thus, the more collisions experienced by a frame, the larger the interval from which K is chosen. For Ethernet, the actual amount of time a node waits is K.512 bit times (i.e., K times the amount of time needed to send 512 bits into the Ethernet) and the maximum value that n can take is capped at 10.Now with respect to the above information, what is the probability that a node chooses K = 4, after the fifth collision in CSMA/CD? The result K = 4 corresponds to a delay of how many seconds on a 10Mbps Ethernet?</li>

 <li>Consider the CRC error detection process. Let us say that the Data (D) = 10110, d (length of the data “D”) = 6, Generator (G) = 1001, and r = 3. As per the CRC error detection process, what is the message finally sent by the sender to receiver. Note that the message sent by the sender is a d+r bit pattern which is a combination of Data (D) bits and the CRC bits (R).</li>

 <li>Consider the 5-bit CRC generator, G = 10011, and suppose that D has the value 1010101010. What is the value of R?</li>

</ol>

<ol start="9">

 <li>Consider the previous problem (Question 8), but suppose that D has the value a. 1001010101.b. 0101101010.c. 1010100000.Find the values of R in each of the cases.</li>

 <li>Consider the parity check method for error detection. Suppose the information content of a packet is the bit pattern 1110 0110 1001 1101 and an even parity scheme is being used. What would the value of the field containing the parity bits be for the case of a two-dimensional parity scheme? Your answer should be such that a minimum length checksum field is used.</li>

 <li>Show (by giving an example) that two-dimensional parity checks can correct and detect a single bit error. Show (give an example of) a double-bit error that can be detected but not corrected.</li>