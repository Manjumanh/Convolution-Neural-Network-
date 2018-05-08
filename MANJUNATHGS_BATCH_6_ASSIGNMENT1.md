# Assignment No 1 

  ### What is covolution ?
  
Convolutional is machine learning technic created based on how human brain works. 
Convolutional is one of the most efficient Neural Networks. It contains one or more convolutional layers each layer gets some inputs and produces a output. Finally it outputs fully connected network as a result. 
Various layers is comprised of convolutions and max poolings.
It is used for Image Classification and Object detection. 
It is used for image processing of high resolution images, because of high 
resolution the computation power required is also high. In convolution we will 
decrease the size of of image by applying various filters and removing unwanted parts of the image. 
Here we will use various channels on input image. Each channel will
output a feature map as a result. 
In Keras it will be done by using the function CONV2D 
It is also a process of finding the subset of images inside a bigger image. It may be object recognition, it may be sound recognition. 
It will find the smaller objects in big image. It will also be used for edge detection of object inside the image. 
We will use the features to find out the specific type of sub object inside the image.  
  
### 1x1 convolution : 
---------------------
It is used to reduce the dimension. Usually used at last iteration after Convolve+ Pooing +convolve +Pooling .....
It is merger, shirker 
It is 7.2% faster than `3*3` filter  
``1*1`` is used to decreased no of input channels as `1*1` will result in 1 output   


Ex: 
* `6*6*1`  `|` `1*1*1` ---> `6*6*1`

* `6*6*3` `|` `1*1*3` ---> `6*6*1` 

* `6*6*32 `  `|`  `1*1*32` ---> `6*6*1` 
* `28*28*192` `|`   `1*1*192 [32 channels]`  ---> `28*28*1  [32 channels]` 


How to create an account on GitHub and upload a sample project :
---------------------
Step 1: Go to the below website to create the account 
        https://github.com/
Step 2: Enter the Details Username, email address and password 
Step 3: Select unlimited public repositories for free 
Step 4: Some personal questions about what you intended to do 
Step 5: Start a new Project, Enter the details about the project Name, Description and select the box "Initialize the repository with a Read me"
Step 6: Create Repository 
Step 7: Open the repository created you will see the README.md file. You can open it and edit[Edit this file option] it. 
         Once edit in down there is option to commit [Commit directly to the master branch.] 
Step 8: Once you commit you will see the commits history
Step 9: There is a option to Upload the file [Upload files] click on it 
Step 10: Choose your files from the local computer.
Step 11: Again commit [Commit directly to the master branch] it 








10 examples of use of MathJax in Markdown : 
-------------------------------------------
$$a = b + c$$
$$c = \sqrt{a^2 + b^2}$$
$$ \alpha = \beta $$   
$$^3/_7$$
$$\frac{n!}{k!(n-k)!}$$
$$k_{n+1}$$
$$\frac{\frac{x}{1}}{x - y}$$
$$\sum_{i=1}^{10} t_i$$
$$\int\limits_a^b$$
$$\int_0^\infty \mathrm{e}^{-x}\,\mathrm{d}x$$
$$\int y \mathrm{d}x$$




















