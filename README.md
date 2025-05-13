# machinelearning-homework-2-naive-bayes-classifier-solved
**TO GET THIS SOLUTION VISIT:** [MachineLearning Homework 2-Naive Bayes classifier Solved](https://www.ankitcodinghub.com/product/machinelearning-homework-2-naive-bayes-classifier-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92066&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MachineLearning Homework 2-Naive Bayes classifier Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Description :

1. Naive Bayes classifier

Create a Naive Bayes classifier for each handwritten digit that support discrete and continuous features.

Input:

1. Training image data from MNIST

You Must download the MNIST from this website and parse the data by yourself. (Please do not use the build in dataset or you’ll not get 100.)

Please read the description in the link to understand the format.

Basically, each image is represented by bits (Whole binary file is in big endian format; you need to deal with it), you can use a char arrary to store an image.

There are some headers you need to deal with as well, please read the link for

more details.

2. Training lable data from MNIST.

3. Testing image from MNIST 4. Testing label from MNIST 5. Toggle option

0: discrete mode

1: continuous mode

TRAINING SET IMAGE FILE (train-images-idx3-ubyte)

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
offset type value

0000 32 bit integer 0x00000803(2051)

0004 32 bit integer 60000

0008 32 bit integer 28

0012 32 bit integer 28

<ol start="16">
<li>0016 &nbsp;unsigned byte ??</li>
<li>0017 &nbsp;unsigned byte ??</li>
</ol>
… … …

xxxx unsigned byte ??

TRAINING SET LABEL FILE (train-labels-idx1-ubyte)

</div>
<div class="column">
description

magic number

number of images

number of rows

number of columns

pixel

pixel

…

pixel

</div>
</div>
<div class="layoutArea">
<div class="column">
offset type

0000 32 bit integer

0004 32 bit integer

<ol start="8">
<li>0008 &nbsp;unsigned byte</li>
<li>0009 &nbsp;unsigned byte</li>
</ol>
… …

xxxx unsigned byte

The labels values are from 0 to 9.

Output:

</div>
<div class="column">
value description

0x00000801(2049) magic number

60000 number of items

<ul>
<li>?? &nbsp;label</li>
<li>?? &nbsp;label</li>
</ul>
… …

?? label

</div>
</div>
<div class="layoutArea">
<div class="column">
Print out the the posterior (in log scale to avoid underflow) of the ten categories (0-9) for each image in INPUT 3. Don’t forget to marginalize them so sum it up will equal to 1.

For each test image, print out your prediction which is the category having the highest posterior, and tally the prediction by comparing with INPUT 4.

Print out the imagination of numbers in your Bayes classifier

For each digit, print a binary image which 0 represents a white pixel, and 1 represents a black pixel.

The pixel is 0 when Bayes classifier expect the pixel in this position should less then 128 in original image, otherwise is 1.

Calculate and report the error rate in the end. Function:

</div>
</div>
<div class="layoutArea">
<div class="column">
1. In Discrete mode:

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Tally the frequency of the values of each pixel into 32 bins. For example, The gray level 0 to 7 should be classified to bin 0, gray level 8 to 15 should be bin 1 … etc. Then perform Naive Bayes classifier. Note that to avoid empty bin, you can use a peudocount (such as the minimum value in other bins) for instead.

2. In Continuous mode:

Use MLE to fit a Gaussian distribution for the value of each pixel. Perform Naive

Bayes classifier.

Sample input &amp; output (for reference only)

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

<pre>10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>Postirior (in log scale):
0: 0.11127455255545808
1: 0.11792841531242379
2: 0.1052274113969039
</pre>
<pre>3: 0.10015879429196257
4: 0.09380188902719812
5: 0.09744539128015761
6: 0.1145761939658308
7: 0.07418582789605557
8: 0.09949702276138589
9: 0.08590450151262384
Prediction: 7, Ans: 7
</pre>
<pre>Postirior (in log scale):
0: 0.10019559729888124
1: 0.10716826094630129
2: 0.08318149248873129
</pre>
<pre>3: 0.09027637439145528
4: 0.10883493744297462
5: 0.09239544343955365
6: 0.08956194806124541
7: 0.11912349865671235
8: 0.09629347315717969
9: 0.11296897411696516
Prediction: 2, Ans: 2
</pre>
<pre>... all other predictions goes here ...
Imagination of numbers in Bayesian classifier:
</pre>
0: 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000011110000000000 0000000000000111111100000000 0000000000001111111110000000

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
59
60
61
62
63
64
65
66
67
68
69
70
71
72
73
74
75
76
77
78
79
80
81
82
83
84
85
86
87
88
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0000000000011111111110000000 0000000000111110001111000000 0000000001111000000111000000 0000000001110000000011100000 0000000011100000000011100000 0000000111100000000011100000 0000000111000000000011100000 0000000111000000000011000000 0000001110000000000111000000 0000001110000000001110000000 0000001110000000001110000000 0000001111000000111100000000 0000000111110011111000000000 0000000111111111110000000000 0000000011111111100000000000 0000000000111100000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000

<pre>... all other imagination of numbers goes here ...
</pre>
9: 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000001111110000000000 0000000000011111111000000000 0000000000111100011000000000 0000000001110000011000000000 0000000001100000011100000000 0000000011100000111100000000 0000000011000001111000000000 0000000001100111111000000000 0000000001111111111000000000 0000000000000011110000000000 0000000000000001110000000000 0000000000000001100000000000 0000000000000001100000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
89 90 91 92 93

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0000000000000000000000000000 0000000000000000000000000000 0000000000000000000000000000

<pre>Error rate: 0.1535
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
2. Online learning

Use online learning to learn the beta distribution of the parameter p (chance to see 1) of the coin tossing trails in batch.

Input:

1. A file contains many lines of binary outcomes:

2. parameter a for the initial beta prior

3. parameter b for the initial beta prior

Output: Print out the Binomial likelihood (based on MLE, of course), Beta prior and posterior probability (parameters only) for each line.

Function: Use Beta-Binomial conjugation to perform online learning. Sample input &amp; output (for reference only)

Input: A file (here shows the content of the file)

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>0101010111011011010101
0110101
010110101101
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

10 11 12

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>$ cat testfile.txt
0101010101001011010101
0110101
010110101101
0101101011101011010
111101100011110
101110111000110
1010010111
</pre>
<pre>11101110110
01000111101
110100111
01101010111
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Output

Case 1: a = 0, b = 0

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3 4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>case 1: 0101010101001011010101
Likelihood: 0.16818809509277344
Beta prior:     a = 0 b = 0
Beta posterior: a = 11  b = 11
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5 6 7 8 9

<pre>10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
case 2: 0110101

Likelihood: 0.29375515303997485 Betaprior: a=11 b=11 Beta posterior: a = 15 b = 14

case 3: 010110101101 Likelihood: 0.2286054241794335 Betaprior: a=15 b=14 Beta posterior: a = 22 b = 19

case 4: 0101101011101011010 Likelihood: 0.18286870706509092 Betaprior: a=22 b=19 Beta posterior: a = 33 b = 27

case 5: 111101100011110 Likelihood: 0.2143070548857833 Betaprior: a=33 b=27 Beta posterior: a = 43 b = 32

case 6: 101110111000110 Likelihood: 0.20659760529408 Betaprior: a=43 b=32 Beta posterior: a = 52 b = 38

case 7: 1010010111

Likelihood: 0.25082265600000003 Betaprior: a=52 b=38 Beta posterior: a = 58 b = 42

case 8: 11101110110 Likelihood: 0.2619678932864457 Betaprior: a=58 b=42 Beta posterior: a = 66 b = 45

case 9: 01000111101

Likelihood: 0.23609128871506807 Betaprior: a=66 b=45 Beta posterior: a = 72 b = 50

case 10: 110100111

Likelihood: 0.27312909617436365 Betaprior: a=72 b=50 Beta posterior: a = 78 b = 53

case 11: 01101010111 Likelihood: 0.24384881449471862 Betaprior: a=78 b=53

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
54

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>Beta posterior: a = 85  b = 57
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Case 2: a = 10, b = 1

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

<pre>10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
case 1: 0101010101001011010101 Likelihood: 0.16818809509277344 Betaprior: a=10 b=1 Beta posterior: a = 21 b = 12

case 2: 0110101

Likelihood: 0.29375515303997485 Betaprior: a=21 b=12 Beta posterior: a = 25 b = 15

case 3: 010110101101 Likelihood: 0.2286054241794335 Betaprior: a=25 b=15 Beta posterior: a = 32 b = 20

case 4: 0101101011101011010 Likelihood: 0.18286870706509092 Betaprior: a=32 b=20 Beta posterior: a = 43 b = 28

case 5: 111101100011110 Likelihood: 0.2143070548857833 Betaprior: a=43 b=28 Beta posterior: a = 53 b = 33

case 6: 101110111000110 Likelihood: 0.20659760529408 Betaprior: a=53 b=33 Beta posterior: a = 62 b = 39

case 7: 1010010111

Likelihood: 0.25082265600000003 Betaprior: a=62 b=39 Beta posterior: a = 68 b = 43

case 8: 11101110110 Likelihood: 0.2619678932864457 Betaprior: a=68 b=43 Beta posterior: a = 76 b = 46

case 9: 01000111101

Likelihood: 0.23609128871506807 Betaprior: a=76 b=46 Beta posterior: a = 82 b = 51

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>46
47
48
49
50
51
52
53
54
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
case 10: 110100111

Likelihood: 0.27312909617436365 Betaprior: a=82 b=51 Beta posterior: a = 88 b = 54

case 11: 01101010111 Likelihood: 0.24384881449471862 Betaprior: a=88 b=54 Beta posterior: a = 95 b = 58

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
3. Show the distribution of online learning

Following the result of 2. Online learning, try to show distribution of prior, likelihood function and posterior step by step.

For example, the prior is given by a beta distribution with parameters a=2, b=2, and the likelihood function, given with N=m=1, corresponds to a single observation of x=1, so that the posterior is given by a beta distribution with parameters a=3, b=2.

4. Prove Beta-Binomial conjugation

Try to proof Beta-Binomial conjugation and write the process on paper.

※ You should write down the proof process on paper and take a picture. When you hand in HW02, it must contain your code and picture.

l NOTE:

<ul>
<li>¡ &nbsp;Use whatever programming language you prefer.</li>
<li>¡ &nbsp;You can’t use numpy.random.beta in HW02. That would be great if you
implement all distribution by yourself.
</li>
<li>¡ &nbsp;HW02 must contain your code and proof process (can be .pdf or any image
format).
</li>
</ul>
</div>
</div>
</div>
