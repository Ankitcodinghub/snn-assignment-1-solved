# snn-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [SNN Assignment 1 Solved](https://www.ankitcodinghub.com/product/snn-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90930&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SNN Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="layoutArea">
<div class="column">
&nbsp;

This project is conceptually mostly math-intensive.

Part 1: Demonstrate how a neuron works

A neuron, the smallest block of a neural network, takes the input, performs mathematical operations on it, and returns an output. The operations performed are as follows: multiply each input by a weight, get the sum of the above and add a bias value of b, and finally input the sum into the activation function

Create a Python Module called SimpleNeuron.

</div>
</div>
<div class="layoutArea">
<div class="column">
–

– –

</div>
<div class="column">
Define function as the Sigmoid function (activation function) f(x) = 1 / (1 + e^(-x) in order to transform any value x into a new value between (0,1)

Define a class called SimpleNeuron which takes in two variables: weights and bias.

Define another function (feedforward function) that estimates the scalar/dot product of inputs with weights, then adds the bias value b. This sum is then inputted into the sigmoid function, and we return the result

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1. A neuron

Figure 2. Neural network of 3 Neurons

</div>
</div>
<div class="layoutArea">
<div class="column">
Part 2: Demonstrate how a group of 3 neurons work

</div>
</div>
<div class="layoutArea">
<div class="column">
A simple Neural Network consists of 2 inputs x1 and x2, 2

process layer neurons, and 1 output neuron. Assuming fixed

values for weights and bias, this NN feeds array x to n1 and n2.

The results from these 2 neurons are then fed into the output neuron. Each time an input is passed into a neuron, the mathematic operations

Create a Module called SimpleNeuralNetwork

<ul>
<li>– &nbsp;Define class Simple Neural Network of fixed weight and bias values</li>
<li>– &nbsp;Create 3 different neurons: neuron 1, neuron 2, output neuron.</li>
<li>– &nbsp;Define new feedforward function with input x: it takes x and performs the original feedforward
function defined in Part 1 on neuron 1 and neuron 2. Then it takes the two results, and uses it as input to perform the feedforward function on the output neuron. Return result.

Part 3: demonstrate how to train our simple Neural Network

We can use the MSE (mean square error) function to measure how far the predicted result by the NN is from reality. To do so, find the average of the squared value of (predicted value minus true value). The
</li>
</ul>
</div>
</div>
<div class="layoutArea"></div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
larger this number, the bigger the loss. To reduce loss, we must tweak each weight. This can be done through the partial derivative: ∂Loss/∂weight, which we calculate as the product of predicted value times (sigmoid derivative of previous outputs of neuron1 and 2) times (sigmoid derivative of values from real life). Based on the result, reduce or increase the value of the weight as needed, which decreases Loss.

New weight value = old weight value – (learning rate)*( ∂Loss/∂weight) Create a Python Module called TrainedNeuralNetwork

<ul>
<li>– &nbsp;Define the MSE = mean((true value – predicted values)^2). We want to minimize this value.</li>
<li>– &nbsp;Define the derivative of the sigmoid: f'(x) = f(x) * (1 – f(x))</li>
<li>– &nbsp;Define new class TrainedNN
input x is an array of 2 values, 2 neuron layer, 1 output neuron
</li>
<li>– &nbsp;Initialize 6 weights as random numbers (2 weights connecting input to neuron 1, 2 weights
connecting input array to neuron 2, 2 weights connecting the results from the first 2 neurons to the output neuron)

3 bias values assigned as random numbers
</li>
<li>– &nbsp;Define train function

Declare variable learn rate (ie. 0.1)

Declare variable e as number of loops to train the NN (adjust weights)

Create loop that runs e times

Use feedforward function on the input to get results predicted by current NN

Compare predicted results with true results

For each of the neurons, adjust weight = old weight value – (learning rate)*( ∂Loss/∂weight), where ∂Loss/∂weight is calculated utilizing the derivative of the sigmoid defined above

At the end of the loop, the weights will have adjusted and when we try inputting data, the neural network will make the best guess it can.
</li>
</ul>
</div>
</div>
</div>
