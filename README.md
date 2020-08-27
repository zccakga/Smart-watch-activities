# Identifying sedentary and active activities using a smart watch
<h3>Aims</h3>
<p> The aim of this project was to find out how well a smart watch can discern between sedentary activites and 'active' activities that are <b>most common</b> in the average person's life. The activities chosen for this analysis were therefore split into two categories:</p>
<p>Sedentary activities:
 <ul>
  <li>Sitting</li>
  <li>Typing</li>
  <li>Writing</li>
 </ul
</p>
<p>Active activities:
 <ul>
  <li>Walking</li>
  <li>Jogging</li>
  <li>Stairs</li>
  <li>Standing</li>
  <li>Kicking(football)</li>
  <li>Playing catch w/tennis ball</li>
  <li>Dribbling</li>
  <li>Folding clothes</li>
 </ul
</p>

<h3>Database description</h3>
<p>The database was downloaded from https://archive.ics.uci.edu/ml/datasets/WISDM+Smartphone+and+Smartwatch+Activity+and+Biometrics+Dataset+# and further information on the dataset can be found in the database folder. In a nutshell, the database contains data collected from 51 participants, who were asked to perform a number of diverse activities for 3 minutes. The data set contains sensor data from the phone’s accelerometer, phone’s gyroscope, watches’ accelerometer, and watches’ gyroscope, which were collected at a rate of 20 Hz.</p>

<h3>Findings</h3>
<p>Using decision trees from the sklearn module in python it was found that by using the smart watches' accelerometer and gyroscope we can distinguish between sedentary and active activities to a 93% accuracy. Therefore, this data could be used to monitor how many minutes a day in total a person is active and how many minutes they are not. </p>
