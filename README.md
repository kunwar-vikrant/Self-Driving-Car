# <p align="center">Self Driving Car</p>


<p align="center">
  <img width="460" height="300" src="https://healed1337.files.wordpress.com/2018/02/armie.gif">
</p>

Self-driving vehicles are cars or trucks in which human drivers are never required to take control to safely operate the vehicle. Also known as autonomous or “driverless” cars, they combine sensors and software to control, navigate, and drive the vehicle.
This project is to build a model that predicts the vehicles steering angles based on the input it receives from the environment.
Though still in its infancy, self-driving technology is becoming increasingly common and could radically transform our transportation system (and by extension, our economy and society). Based on automaker and technology company estimates, level 4 self-driving cars could be for sale in the next several years.

Various self-driving technologies have been developed by Google, Uber, Tesla, Nissan, and other major automakers, researchers, and technology companies.

## Impacts

Safety is an overarching concern. Many thousands of people die in motor vehicle crashes every year in the United States (more than 30,000 in 2015); self-driving vehicles could, hypothetically, reduce that number—software could prove to be less error-prone than humans—but cybersecurity is still a chief concern.

Equity is another major consideration. Self-driving technology could help mobilize individuals who are unable to drive themselves, such as the elderly or disabled. But the widespread adoption of autonomous vehicles could also displace millions of Americans employed as drivers, negatively impact public transportation funding, and perpetuate the current transportation system’s injustices.

Environmental impacts are a serious concern, and a major uncertainty. Accessible, affordable, and convenient self-driving cars could increase the total number of miles driven each year. If those vehicles are powered by gasoline, then transportation-related climate emissions could skyrocket. If, however, the vehicles are electrified—and paired with a clean electricity grid—then transportation emissions could drop, perhaps significantly.


## How data was recorded

This dataset used in this project is the "Sully Chen's Dataset".It contains mages recorded from a car dashcam with labeled steering angles. Some of the datasets may have timestamps as well.

> Absolutely, under NO circumstance, should one ever pilot a car using computer vision software trained on these datasets (or any home made software for that matter). It is extremely dangerous to use your own self-driving software in a car, even if you think you know what you're doing, not to mention it is quite illegal in most places and any accidents will land you in huge lawsuits.
These datasets are purely for research and statistics, absolutley NOT for application or testing of any sort.

Approximately 63,000 images, 3.1GB. Data was recorded around Rancho Palos Verdes and San Pedro California.

Data format is as follows: > filename.jpg angle,year-mm-dd hr:min:sec:millisec

## Problem Statement

 + Given a input video feed,predict the steering angle of the car.
 
## Models 
 + LSTM deep neural networks along with CNNs are used with hyperparameter tuning.
