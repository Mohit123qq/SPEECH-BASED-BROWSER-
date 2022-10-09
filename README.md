DEMO VEDIO GOOGLE DRIVE LINK (vedio length 7:23 )
https://drive.google.com/file/d/1pMWm--sQGioPNHChRGH8DcqfwDhKCNdy/view?usp=sharing


# SPEECH-BASED-BROWSER-

> **Indian Institute of Technology, Guwahati**

![](IMAGES/media/image1.png)

> Department of Computer Science and Engineering

Project Report

> On\
> **"Speech Based Browser Automation"** Based on\
> Speech Recognition System

**Course: CS566 Speech Processing**

**GROUP NO 19**

> Submitted to
>
> Prof.
>
> P.K..Das

Submitted by:

Keshav Parihar (214101025)

Mohit Kumar (214101029)



**ABSTRACT**

> This document defines a set of evaluation criteria and test methods
> for speech
>
> recognition systems used in searching and retrieving contact details.
> This
>
> report is on the project which detects the contact name and show its
> details

.

**INTRODUCTION**

In this report, we concentrate on the speech recognition programs that
are human-computer

interactive. When software evaluators observe humans testing such
software programs, they

gain valuable insights into technological problems and barriers that
they may never witness

otherwise. . Testing speech recognition products for universal usability
is an important step

before considering the product to be a viable solution for its customers
later. This document

concerns Speech Recognition accuracy in contact searching and retrieving
details, which is a

critical factor in the development of hands-free human- machine
interactive devices. There

are two separate issues that we want to test: word recognition accuracy
and software

friendliness. Major factors that impede recognition accuracy in the
environment noise sources

and system noise.

**However, what is speech recognition?**

Speech recognition works like this. You speak into a microphone and the
computer transforms

the sound of your words into text to be used by your word processor or
other applications

available on your computer. The computer may repeat what you just said
or it may give you a

prompt for what you are expected to say next. This is the central
promise of interactive

speech recognition. You also had to correct any errors virtually as soon
as they happened,

which means that you had to concentrate so hard on the software that you
often forgot what

you were trying to say.

The new voice recognition systems are certainly much easier to use. You
can speak at a

normal pace without leaving distinct pauses between words. However, you
cannot really use

"*natural speech*" as claimed by the manufacturers. You must speak
clearly, as you do when

you speak to a Dictaphone or when you leave someone a telephone message.
Remember, the

computer is relying solely on your spoken words. It cannot interpret
your tone or inflection,

and it cannot interpret your gestures and facial expressions, which are
part of everyday human

communication. Some of the systems also look at whole phrases, not just
the individual words

you speak. They try to get information from the context of your speech,
to help work out the

correct interpretation.

The goal of this project is to define a set of evaluation criteria and
test methods for the

interactive voice recognition systems for searching contact and
retrieving corresponding

details for successful search.

**PROPOSED METHODOLOGY**

Basic requirements to develop this project are as follows:

Windows OS\
Microsoft Visual Studio 2010\
C++ 11 integrated with VS2010\
Recording Module

With the availability of above software, we further proceed in modelling
the logic. The prerequisites of this project are

Basic i/o operations on file\
Pre-processing of speech data\
Feature extraction\
Modelling of extracted feature\
Enhancing model

> With the availability of above tools, we further proceeded. Below is
> the flow chart for our project

![](IMAGES/media/image2.png)

**EXPERIMENTAL SETUP**

This project is divided into following modules: 

**1.Training Module**

**2.Testing Module**

**1.Training Module**

> The flow for training over data is as follows:

1. Record the data as 30 utterance of each word 
1. Extract frames for every utterance 
1. Using local distance analysis (in vector quantization) calculate the observation sequence. 
1. Pass this observation sequence to HMM for model designing. 
1. Now enhance the model using HMM re-estimation algorithm. 

> Now reference model is ready for our project. The training of data is
> not integrated with GUI application. This is different module, which
> will just evaluate reference model.

**2.Testing Module**

System will give instruction what is going on and user is required to follow it. The flow of testing is as follows: 

1. Live recording of data is done when system instruct. 
2. Testing the data with retrained models. 
3. Detect the Search Engine  
4. Detect the word which has to be search 
5. If word is correctly spoken then it opens browser. 
6. If wrong word detected then ,record the input again. 

**WORDS   USED**\ 

**1.START**\
**2.STOP**\
**3.YES**\
**4.SEARCH**\
**5.WIKIPEDIA**\
**6.YOUTUBE**\
**7.SPEECH**\
**8.GOLD**\
**9.CORONA**\
**10.DOLLAR**

> **4.** **SCREEN SHORTS**

**INITIAL WINDOW**

![](IMAGES/media/image3.png)

**WINDOW AFTER START**

![](IMAGES/media/image4.png)

**CLICK TARIN BUTTON**

![](IMAGES/media/image5.png)

**RESULT**\
For offline testing, we took 30 recordings of each word, with
deterministic difference of maximum and second maximum P (O/lambda) we
got 85% accuracy and without considering deterministic difference we got
95% accuracy.

The Spoken word will open in browser with selected Search engine i.e.
YouTube , Google or Wikipedia , Then we search for the available words.



REQUIREMENTS
-->VISUAL STUDIO 2010



FOR EXECUTION OF THE PROGRAM --------------------------------------------------------------------------------

STEP 1 OPEN VISUAL STUDIO 2010 CLICK FILE

STEP 2 CLICK OPEN

STEP 3 CLICK PROJECT/SOLUTION

STEP 4 FIND THE EXTRACTED FOLDER OPEN IT AND GO TO 19_PROJECT FOLDER THE AGAIN CLICK 19_CODE FOLDER 

STEP 5 CLICK ON MyBrowser.sln 

STEP 6 AFTER THE FOLDER OPENS IN VISUAL STUDIO CLICK MyBrowser IN THE SOLUTION EXPLORER

STEP 7 CLICK F5 TO EXECUTE THE PROJECT

STEP 8 CLICK START AND SPEAK "START" TO START 

STEP 9 CLICK SPEAK AND SAY "SEARCH/YOUTUBE/WIKIPEDIA" THE SAY "CORONA/DOLLAR/SPEECH/GOLD" THE DEFAULT BROWSER WILL OPEN

STEP 10 CLOSE THE BROWSER COME BACK TO THE WINDOW TO CONTINUE CLICK CONTINUE AND SAY "YES" THEN AGAIN SAY "SEARCH/YOUTUBE/WIKIPEDIA" THEN SAY "CORONA/DOLLAR/SPEECH/GOLD" THE DEFAULT BROWSER WILL OPEN

STEP 11 TO TRAIN CLICK TRAIN AND TYPE THE WORD THEN CLICK RECORD TO RECORD 20 TIMES

STEP 12 TO CLOSE IT CLICK CONTINUE AND SPEAK "STOP"
