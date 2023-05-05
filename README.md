Download Link: https://assignmentchef.com/product/solved-ct5133-ct5145-assignment-1
<br>



<h1>Module Assessment</h1>

<ul>

 <li>Final exam (60%)

  <ul>

   <li>Sample questions will be provided closer to the exam time</li>

  </ul></li>

 <li>Continuous assessment (40%)

  <ul>

   <li>Assignment 1: 20% (due at end of Week 6)</li>

   <li>Assignment 2: 20% (due at end of Week 11)</li>

   <li>Details and specific deadlines will be posted on Blackboard</li>

   <li>The two assignments will be substantial multi-week programming assignments.</li>

  </ul></li>

</ul>

<h1>Deep Learning Assignment 1</h1>

<ul>

 <li>In this assignment, you will implement a deep neural network from scratch

  <ul>

   <li>Multi-part assignment, drawing on material covered each week</li>

   <li>You are expected to start work on it immediately; it is NOT recommended to wait until near the deadline</li>

  </ul></li>

 <li>You must use a Jupyter Notebook:

  <ul>

   <li>Python recommended but R is OK too</li>

   <li>You can use low-level functionality of numpy and scikit-learn, but <strong>not </strong>their implementations of anything core (e.g. optimisers, grad descent etc.)</li>

  </ul></li>

</ul>

<h1>1-Person or 2-Person Assignment: You Choose</h1>

<ul>

 <li>You can do the assignment on your own or you can join with 1 other person (no more)

  <ul>

   <li>Final part will involve separate contributions by both people</li>

  </ul></li>

 <li>Policy on two-person submissions:

  <ul>

   <li>You are encouraged to work in pairs for Parts 1-4, but you cannot collaborate with other people in the class beyond that.</li>

   <li>Part 5 must be done twice for a 2-person assignment.</li>

   <li>Your documentation and code must be clear about what contributions each person made; it is <strong>not </strong>sufficient to say something like“we both worked on everything together”.</li>

   <li>Across all parts of the assignment, I may award different marks to each person doing a 2-person assignment if I feel that their contributions are not equal.</li>

  </ul></li>

</ul>

<h1>Part 1: Implement Logistic Regression</h1>

<ul>

 <li>Logistic Regression

  <ul>

   <li>Use Jupyter Notebook (Python or R) to implement a neural network approach to logistic regression (no hidden layers, one output node)</li>

   <li>Work in pairs: note contributions of both people (larger groups not allowed)</li>

   <li>Your code must handle different numbers of inputs and different numbers of training cases, but you don’t have to support more than one output node</li>

  </ul></li>

 <li>Recommended to follow my notes closely

  <ul>

   <li>Post questions on discussion forum if there are gaps/inconsistencies, or if you are unclear about anything</li>

   <li>No plagiarism! ANY plagiarism will result in 0 for full assignment</li>

   <li>Reference ALL sources you used</li>

   <li><strong>Do not submit code taken from the web</strong></li>

  </ul></li>

</ul>

<h1>Part 2: Easy Tasks</h1>

<ul>

 <li>I will supply two fairly small datasets:

  <ul>

   <li>One will be linearly separable (almost or fully), the other will not</li>

   <li>I will provide sample Python code to load and plot the datasets; you are allowed to use this code in your own assignment</li>

  </ul></li>

 <li>Divide each dataset randomly into:

  <ul>

   <li>Training set (70%): use for main training</li>

   <li>Validation set (15%): use for tuning,</li>

  </ul></li>

</ul>

e.g. selecting learning rates

– Test set (15%): held out set for final performance evaluation

<ul>

 <li>Train a logistic regressor using your code from Part 1, and see how it performs on both datasets</li>

</ul>

<h1>Part 3: Implement and Test a Shallow Neural Network</h1>

<ul>

 <li>Implement a shallow neural network

  <ul>

   <li>Start with your logistic regression code – Again, follow my notes as closely as possible</li>

   <li>Your code must support different numbers of input nodes and different numbers of nodes in the hidden layer; you don’t have to</li>

  </ul></li>

</ul>

support more than one output node

<ul>

 <li>No need to support more than 1 hidden layer</li>

</ul>

<ul>

 <li>Test your implementation on the two small datasets:

  <ul>

   <li>Is it able to handle the linearly separable data? (I hope so)</li>

   <li>Does it perform better than the logistic regression implementation on the dataset that is not linearly separable?</li>

  </ul></li>

</ul>

<h1>Part 4: Challenging Task</h1>

<ul>

 <li>Image recognition is one task now tackled with ML, that was considered “very hard” not long ago

  <ul>

   <li>We will use the CIFAR-10 dataset <a href="https://www.cs.toronto.edu/~kriz/cifar.html">https://www.cs.toronto.edu/~kriz/cifar.html</a></li>

   <li>Each image is 32×32, 3 colour channels (RGB):</li>

  </ul></li>

</ul>

Use just 1 colour or convert to greyscale;

Convert to vector of 1024 floats

<ul>

 <li>50k training images, 10k testing images: you can select random subsets (e.g. 1 batch)</li>

 <li>1 hidden layer (larger than first case), 1 output</li>

</ul>

<ul>

 <li>You must try to distinguish between <strong>2 classes only:</strong>

  <ul>

   <li>Send me an email message saying the name of the 2 people in your group and I’ll give you a pair of images.</li>

  </ul></li>

 <li><em>PhD students: If you want to use a different dataset related to your research, contact me in advance for agreement </em></li>

</ul>

<h1>Part 5: Deep Learning Enhancements</h1>

<ul>

 <li>This part must be done individually:

  <ul>

   <li>Do not do it with the other member of your group</li>

   <li>Include 2 separate sections in your report about what each of you did in Part 5</li>

  </ul></li>

 <li>Each group member: pick one enhancement that is characteristic of deep learning

  <ul>

   <li>The two group members have to pick different enhancements from each other</li>

   <li>implement your enhancement</li>

   <li>Test how well it works relative to the shallow NN on the image dataset</li>

  </ul></li>

</ul>




<em>Deep Learning</em>