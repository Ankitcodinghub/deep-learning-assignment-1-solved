# deep-learning-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [Deep-Learning Assignment 1 Solved](https://www.ankitcodinghub.com/product/deep-learning-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93341&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Deep-Learning  Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Tasks and Dataset

Image classification (Sign language letters)

In this assignment there are two separate tasks both involving classification of sign language letters.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Images of example sign language letters and their labels

Task 1 –

The first task is to train two models to recognize sign language letters and compare their performances. You can choose any two models (Neural Networks, multi-class logistic regression, multi-layer perceptron (MLP), Support Vector Machines (SVM), K-Nearest Neighbor, etc.) for comparison. You will split your training data (train data label.npz) into training and validation sets to train your models and finding the optimal parameters, respectively. You will test the performance of the two models on the same test dataset (test data label.npz)

3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
You will use:

• training part to train your model,

</div>
</div>
<div class="layoutArea">
<div class="column">
• validation part to find the optimal parameters of your model,

• test part to evaluate the model with the optimal parameters found on the validation set.

The training and test datasets consist of images of sign language letters and their labels as shown in Figure 2. The labels correspond to the place of the letter in the English alphabet (0-25). Note that there are no cases for J=9 or Z=25 because of gesture motions. For example: A is 0, B is 1, I is 8, K is 10, and so on. In total, there are 24 classes excluding J=9 and Z=25.

Figure 2: Example images and labels

The training dataset named train data label.npz and the test dataset named test data label.npz are available for download on the canvas homepage. This file contains two python lists of (1) images (as numpy arrays) and (2) corresponding labels (indexed by their position in the list). You can load this data by using the code snippet shown in Figure 3.

Figure 3: Code snippet you can use to load the training and the test data (images and labels). train data and train label correspond to training images and labels, respectively. Similarly, test data and test label correspond to test images and labels, respectively.

4

</div>
</div>
<div class="layoutArea">
<div class="column">
Machine Learning Assignment

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Machine Learning Assignment

Please make sure you have all the data available to you. Training data consists of 27455 images and labels in total. Test data consists of 7172 images and labels in total. Each training and test instance is a 784 dimensional vector, which can be represented as an image of size 28 × 28 by reshaping.

Task 2 –

In the second task you will use the classifiers trained in the first task (or you can train new classifiers) to identify a series of n sign language letters in an image of size 28 × 200. n can take values in the range [1, 5] randomly. Letters are overlaid on a noisy image as shown in the Figure 5.

Figure 4: An example test image. The label for this particular image is ‘180019’. The letters in the image are: ‘SAT’. You can encode/decode the label as: S = 18, A = 00, T = 19, considering the position of the letter in the English alphabet.

Figure 5: Another example test image. The label for this particular image is ‘0418182407’. The letters in the image are: ‘ESSYH’. You can encode/decode thelabelas: E=04,S=18,S=18,Y=24,H=07,consideringtheposition of the letter in the English alphabet.

Note that the label of an image is generated by concatenating the positions of its letters in the English alphabet. For example, if the letters in the image are: ‘ABCD’, the label for this image will be ’00010203’. A dataset of sample test images with their true labels will be provided.

Top-5-accuracy: In this task, top-5-accuracy measure will be used for evalu- ation. Accordingly, you will make 5 predictions for each image. If 1 out of the 5 predictions is correct (same as the true label) then it is qualified as a correct classification. For example, if the letters in the image are ‘abcd’ (true label = 00010203) and the predicted labels are:

[ 01020310 , 0001020304 , 010203 , 02 , 00010203 ]

then this is classified as a correct prediction since one of the predictions of the classifier is correct.

5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Test Dataset

</div>
</div>
<div class="layoutArea">
<div class="column">
test images task2.npy is a list of 10000 images. For each image your designed classifier will make 5 predictions. Each row in the prediction.csv file will contain 5 predicted labels separated by comma.

Thus the final prediction.csv is a 10000 × 5 file (no header, no index) where kth row represents the predictions corresponding to the kth image in the test set. A snapshot of how the final prediction.csv should look like is shown in Figure 6. Make sure you predict the labels of the images in the same order as they are listed in the test images task2.npy.

As a sanity-check, make sure that the first two images in the test images task2.npy correspond to labels: ‘19181012’ (TSKM); ‘2423142413’ (YXOYN) and the last image corresponds to label: ‘231807’ (XSH) respectively.

Figure 6: Example prediction.csv. This example shows 8 rows and 5 columns. The prediction.csv you submit must contain 10000 rows and 5 columns

Method

There are four important restrictions on the method used:

<ul>
<li>The method should be fully automatic, that is, re-running your code should re-create your prediction file.</li>
<li>The method should not be hard-coded in any way. That is, if a separate set of test-images are provided as input to the code, it should run and predict the labels without any changes in the code.</li>
<li>Every software component used should be open-source and possible to install locally. This means that you cannot use proprietary closed-source software or access to a web service to carry out any data processing.</li>
<li>The method should not use any external dataset which overlaps with the provided data. If you wish to make use of external data in your solution ask the instructor via the course forum to confirm that this data is allowed.
6
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Machine Learning Assignment

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Hint

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>For task 1, you can use the train test split function from sklearn.model selection to split your data into training and validation sets.</li>
<li>For task 2, you can consider using score/probability value outputs of the classifier. You can try using these scores to find the letters and make guesses in the test image.</li>
<li>Make sure your predictions do not contain 09 or 25 as J=9 and Z=25 are not included in the dataset.
References

[1] Original Dataset: Sign Language MNIST https://www.kaggle.com/ datamunge/sign-language-mnist
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Machine Learning Assignment

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
