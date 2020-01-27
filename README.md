# Social Network Analysis

Social network anlaysis has found utility is institutional, classroom and analyses of networked data in socially-based educational games. However, the utility of the method largely rests on being able to ascribe meaning to the **structure of the network**. Without meaningful interpretation of structure there is no added value to a networked model, you will find more success simply regressing your outcome against student characteristics.  Understanding measures of centrality and network structure in SNA are therefore an important, though difficult, aspect of the method. As with all SNA work, the vocabulary can be daunting though the ideas are relatively intuitive.

![socialnetwork](http://www.pacificrisa.org/wp-content/uploads/2013/11/Full-Network-Region-Degree-Fruchterman-Reingold-12K-4000x4000-1024x1024.jpg)

## Project Objective:

The purpose of this project is to build several social network diagrams (graphs/sociograms) of a school classroom and then analyzing and interpreting both centrality measures and clusters within the network. In particular, the data were collected by Vickers & Chan from 29 seventh grade students in a school in Victoria, Australia. Students were asked to nominate their classmates on a number of relations including the following three "layers":  

1. Who do you get on with in the class?  
2. Who are your best friends in the class?  
3. Who would you prefer to work with? 

## Datasets: 

The data was retrieved from:

Representing Classroom Social Structure. Melbourne: Victoria Institute of
Secondary Education, M. Vickers and S. Chan, (1981)

* best.friends.csv
* work.with.csv
* get.on.with.csv

## Class Social Networks:

The nodes are colored based on the student's gender. 

![BestFriends](https://github.com/lizarova777/Social_Network_Analysis_Project2/blob/master/Class_Social_Network.png)

__The D3.js visualization link is found here: [Class Social Network Dashboard](https://cdpn.io/al3868/debug/gObExjg)__

The HTML, CSS, and JavaScript (JS) files are found in the repository. 

**Preview**:

![visualization](https://github.com/lizarova777/Social_Network_Analysis_Project2/blob/master/D3ClassSocialNetworks.gif)

As one can see, the social network of the class and the relationship between students changes in different contexts. 

## Result Interpretation:

In this 7th grade class, it seems that the student who everyone perceives to be their best friend is not the one who many students get on with in class and prefer to work with. Furthermore, by visually inspecting the networks in regards to students' gender, female students tend to be one side of the network while male students tend to be on the other side of the network. In other words, students prefer to have social ties with those of same gender. Nonetheless, boys and girls do communicate with each other in the class. This is illustrated by examining the student with the ID number 12, with whom many boys in class get on with. In terms of reciprocity, many relationships are not mutual, especially when it comes to who gets on with who in class. Nevertheless, the teacher can assign students into groups where the is an equal proportion of boys and girls in regards to group work. Also, the teacher should help students with ID numbers 18 and 25 to interact with others in class.