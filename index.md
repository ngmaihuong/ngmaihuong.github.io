---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---

# Overview

## VietLit

<p align="left">
  <img src="https://github.com/ngmaihuong/ngmaihuong.github.io/blob/master/assets/img/VietLitlogo.png?raw=true"  width="400">
</p>

[VietLit](https://vietlit.com/) is an online literature platform whose goal is to honor original works by Vietnamese authors and nurture a passionate and supportive community for online Vietnamese literature. Founded in 2020 by a small group of Vietnamese youths living across several time zones, VietLit distinguishes our product by our emphasis on authenticity. We put effort into screening all the works uploaded to our website to ensure they meet our quality requirements and nurturing close professional relationships with authors. With our values being *quality*, *creativity*, *familiarity*, *culture* and *orientation*, we are a Viet website created for Viet people and those who are interested in listening to our authentic voices and learning about our culture.

During my time with VietLit, we went through **three** big phases: (1) researching the market and building internal teams, (2) launching and running social media campaigns to build an audience base for our product, and (3) launching and maintaining our product – VietLit website. The team grew from 6 to 40 people divided by functions, our social media presence expanding from Facebook to Instagram and Youtube, our number of organic followers on [Facebook](https://www.facebook.com/vietlit.community) (our main promotional channel) growing to 5K+ and our number of website users increasing everyday.

For more details, visit [HERE](https://ngmaihuong.github.io/vietlit/).

## Saigon Dating Project

<p align="left">
  <img src="https://github.com/ngmaihuong/saigondatingproject/blob/master/assets/img/logo.png?raw=true"  width="400">
</p>

[Saigon Dating Project](https://www.facebook.com/saigondatingproject/) is a 3-month experimental project by a group of thirteen Vietnamese youths studying all over the globe to explore the dating and romantic relationship landscape in Ho Chi Minh City, Vietnam. Our aims are to understand people's dating behaviors and preferences specific to Ho Chi Minh City (HCMC), Vietnam with its very own culture and way of life. Even though "brand name" apps such as *Tinder*, *Bumble* and *OkCupid* have their presence in HCMC, their difficulty in catering for the Vietnamese audience partially explains their stigmatization and slow growth in this city. Therefore, as a predominantly HCMC-native group of young people, many of whom have been exposed to the Western cultures where dating apps are the new normal, we want to learn more about our own culture and people, and thus try out our ideas in the form of social media campaigns and dating events to see what works and what doesn't.

To accomplish this goal, we develop a [Qualtrics survey](https://bit.ly/3erPyMY) which covers a wide range of topics, from demographics, personal preferences when it comes to dating partners to a personality test based on pop-psychological classification systems, namely *Myers-Briggs Type Indicator (MBTI)* and *Five Love Languages*. Towards the end of the survey, we have an optional section where we dive deep into the respondents sense of self, their concerns and challenges when it comes to romantic relationships and their opinions on dating programs/organizations. The number of responses that we have received so far exceeds our modest initial expectations, with more than 500 responses from various demographic groups.

For more details, visit [HERE](https://ngmaihuong.github.io/saigondatingproject/).

## Case Study: Talent Acquisition across Online Platforms at a Tech Start-up in New York City

<p align="left">
  <img src="https://github.com/ngmaihuong/ngmaihuong.github.io/blob/master/assets/img/TApic.jpg?raw=true"  width="400">
</p>

Together with technological advances in all facets of the business is the gradual disappearance of so-called "traditional recruiting", that is recruiting through newspapers, posters and cold calls. Multiple online career platforms such as Indeed, Glassdoor, LinkedIn, etc. have been introduced to help businesses with their hiring needs. The effectiveness of these platforms are undeniable as they have saved a lot of time for both the employers when hiring and the candidates when job searching. However, such replacement might have simultanously introduced new nuances and patterns in the Talent Acquisition dynamics. This is my initial hypothesis.

For this case study, I employ Data Analytics practice in exploring the Talent Acquisition work. Such a combination has become a trending topic in recent years, following the explosion of Big Data and Machine Learning applications in Business. By examining a 30K-entry candidates dataset from a NYC tech start-up, the ultimate question that I ask is **whether it is possible to predict a candidate’s application outcome given the objective attributes of their application**. To find the answer, I apply what [David Donoho](https://courses.csail.mit.edu/18.337/2015/docs/50YearsDataScience.pdf) called the "predictive culture's secret sauce" - the *Common Task Framework methodology* - to the *Naive Bayes classifier* to test my model.

For more details, visit [HERE](https://drive.google.com/file/d/1BI6OODUfldydWnKCGVrgxqxB4z1XAPbs/view?usp=sharing).

## Visualizing Probabilistic Uncertainty through Samples with Python

<p align="left">
  <img src="https://github.com/ngmaihuong/applied-ds-su20/blob/master/assets/img/Week3-assignment.gif?raw=true"  width="400">
</p>

This custom visualization is among the assignments for my [Applied Plotting, Charting & Data Representation in Python](https://www.coursera.org/learn/python-plotting/home/welcome) course, which has taught me how to report and build chart using the *matplotlib* library in Python. The assignment is based on a paper by [Ferreira et al.](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/Ferreira_Fisher_Sample_Oriented_Tasks.pdf) which is concerned with the challanges users face when making decisions given uncertain probabilistic data generated through samples. The data for this visualization is generated using the following codes:
```
np.random.seed(12345)

df = pd.DataFrame([np.random.normal(32000,200000,3650), 
                   np.random.normal(43000,100000,3650), 
                   np.random.normal(43500,140000,3650), 
                   np.random.normal(48000,70000,3650)], 
                  index=[1992,1993,1994,1995])
```
For full codes, visit [HERE](https://github.com/ngmaihuong/applied-ds-su20/blob/master/C2-Week3-assignment.py).
