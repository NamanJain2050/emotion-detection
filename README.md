# Emotion detection in Twitter Dataset

Supervised classification task is to detect emotions in raw text. We've downloaded and prepared data from two different sources.

## Model architecture

Model inspired from here: https://arxiv.org/abs/1610.08815 <br>
This model is used on both datasets

<p align="center">
  <img src="https://github.com/NamanJain2050/emotion-detection/blob/master/images/model_01.png" alt="model_01"/>
</p>

## Dataset I

Source: http://saifmohammad.com/WebPages/EmotionIntensity-SharedTask.html <br>

<table>
  <tr>
    <th></th>
    <th>fear</th>
    <th>joy</th>
    <th>anger</th>
    <th>sadness</th>
  </tr>
  <tr>
    <td>Train</td>
    <td>455</td>
    <td>333</td>
    <td>327</td>		
    <td>317</td>		
  </tr>
  <tr>
  	<tr>
    <td>CV</td>
    <td>114</td>
    <td>83</td>
    <td>82</td>		
    <td>79</td>
  </tr>
    <td>Test</td>
    <td>471</td>
    <td>356</td>
    <td>348</td>		
    <td>327</td>
  </tr>
  <tr>
    <td>Total</td>
    <td>569</td>
    <td>416</td>
    <td>409</td>		
    <td>396</td>
  </tr>
</table> 

### Results

Classification report: <br>
<p align="center">
  <img width="500" height="500" src="https://github.com/NamanJain2050/emotion-detection/blob/master/images/report_1.png" alt="class_report"/>
</p>
<br>
Metric Plot: <br>
<p align="center">
  <img width="500" height="500" src="https://github.com/NamanJain2050/emotion-detection/blob/master/images/metric_1.png" alt="class_report"/>
</p>
<br>
Loss Plot: <br>
<p align="center">
  <img width="500" height="500" src="https://github.com/NamanJain2050/emotion-detection/blob/master/images/loss_1.png" alt="class_report"/>
</p>
<br>