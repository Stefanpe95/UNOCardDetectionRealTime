# Tensorflow UNO cards Object Detection in Real-Time
<p>This project is the process of learning to train and evaluate using specific model from Tensorflow Object Detection API and learn your model to recognize UNO cards</p>

## Model

<p>Model used in this project is <b>MobileNetV2 FPN Lite 320x320</b></p>

## Train results
<img src="https://i.postimg.cc/Y0GdD4zD/Screenshot-2021-12-06-231832.jpg">

## Evaluation results
<img src="https://i.postimg.cc/hj3C08T7/Screenshot-2021-12-06-232251.jpg">

## Final results

<table>
  <tr>
    <td><img src="https://i.postimg.cc/k4518Y6m/download.png"></th>
    <td><img src="https://i.postimg.cc/Y0ZstNSw/download-1.png"></th>
  </tr>
  <tr>
    <td><img src="https://i.postimg.cc/Bv4wZnJt/download-2.png"></td>
    <td><img src="https://i.postimg.cc/Jzb2WkV9/download-3.png"></td>
    <td><img src="https://i.postimg.cc/xd5pXVd5/download-4.png"></td>
  </tr>
</table>


## Real Time Results
<img src="https://i.postimg.cc/mZK4LCJD/ezgif-com-gif-maker.gif">

## Steps
<br />
<b>Step 1.</b> Clone this repository
<br/><br/>
<b>Step 2.</b> Create a new virtual environment 
<pre>
python -m venv od_uno
</pre> 
<br/>
<b>Step 3.</b> Activate your virtual environment
<pre>
source od_uno/bin/activate # Linux
.\od_uno\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 4.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=od_uno
</pre>
<b>Step 5.</b> Start jupyter notebook in your kernel,go through all steps and install required modules and APIs,and start inference of the model