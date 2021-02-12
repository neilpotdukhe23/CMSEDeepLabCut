CMSE Project Proposal: DeepLabCut

Image link: https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.taconic.com%2Ftaconic-insights%2Fquality%2Fmachine-learning-animal-observation.html&psig=AOvVaw3jhOC7pBQOCEsKoDTQnF4N&ust=1613185867785000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKiAguuv4-4CFQAAAAAdAAAAABAR

Abstract:

DeepLabCut is a software package for markless pose estimation of animals or humans performing various tasks. It helps quantifying behaviors which 
is crucial for answering scientific questions. DeepLabCut uses a human pose estimation algorithm to allow a user to train a neural network to precisely track 
user defined features. It allows researchers to take a video and digitally label specific body parts in a few dozen frames, the package then learns how to 
pick out those same features in the rest of the video. A lot of research hinges on understanding what animals/humans are doing by quantifying what they are doing
on video. I believe that this is very useful for researchers and will save them countless hours. DeepLabCut will help propel scientific research. In the video
above, we can see how DeepLabCut tracks the key-points throughout the video. DeepLabCut is a python package that we have to clone. A lot of computation is used
when we train the deep neural network and when there is active learning. It is possible to run it on a standard computer with a CPU but it would compromise on
speed. We can try running it on GPU&#39;s. I am hoping to benchmark this on a CPU and then run it on GPUs and benchmark it. A successful outcome will be if we
can speed up the labeling process when the network trains.

Schedule:

- Thursday February 11 - Project Proposal Milestone Due
- Week of February 15 – work on installing it in HPCC
- Week of February 22 – HPCC install
- Week of March 1 – time it on a CPU
- Week of March 8 – work on timing it on a GPU
- Week of March 15 – upload on HPCC
- Week of March 21 – upload on HPCC
- Week of March 22 – create an easy way to reserachers to upload videos and get data
- Thursday March 25 - Project Part 1 Due
- Week of March 28 Optimize https://static1.squarespace.com/static/57f6d51c9f74566f55ecf271/t/5eab5ff7999bf94756b27481/1588289532243/NathMathis2019.pdf
- Week of March 29 Optimize + create an easy way to reserachers to upload videos and get data
- Week of April 5 Optimize + create an easy way to reserachers to upload videos and get data
- Week of April 12 Optimize + create an easy way to reserachers to upload videos and get data
- Thursday April 15 - Final Project due

Software Exploration:

[https://github.com/DeepLabCut/DeepLabCut](https://github.com/DeepLabCut/DeepLabCut)

We will also need TensorFlow and wxPython.

This is a python package and I will have a list of instructions for submitting videos to the package and getting data.

Benchmark and Optimization:

DeepLabCut will work on CPU&#39;s but will be faster if ran on GPUs so I will work running it on that. I will try to optimize the neural network code 
specifically.
