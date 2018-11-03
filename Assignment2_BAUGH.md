 **Raven Baugh**

 **Assignment 2: Network of American Studies Program**



# ***Introduction***


What are the components of the American Studies program at the University of Richmond? Why is it called ‘Studies’ rather than a more specific subject area? Who are the core faculty for the American Studies program? These are some of many questions I considered before building my network assignment. M. E. J. Newman states that “a network is, in its simplest form, a collection of points joined together in pairs by lines” (Newman-*Networks: An Introduction*- 2010). These lines create interlocking systems that map interdependency and relationships (Weingart-JDH-2011).This is helpful to display relationships between subjects and to convey patterns of connection between various items. For networks, the subjects are the nodes and the connections are the edges that together create a larger interlocking system (Newman-*Networks: An Introduction*- 2010). 


# ***Process***


Firstly, I want to address why I selected this network and then explain my process for collecting data. I decided to create a network on American Studies as I wanted more insight on the connections between individuals, gender, and subjects that make up the interdisciplinary program. This would also reveal how diverse, in regards to subject matter and gender, that the program is. I selected my data from the University of Richmond’s bannerweb site. There, I went into the class listings for American Studies from Fall 2015 to Spring 2019. This gave me four academic years of data to create my network. This time frame allowed for more subjects and professors to be listed that taught in this program. 

 I decided to select the professors and the attributes from each course listing. I did this because it is important to consider the professors teaching the courses as each professor has a different expertise or specialized knowledge that can be applied to a class. As for attributes, attribution is the method that the university uses to assign four letter identifiers to courses to readily conveywhat subjects or programs are within a course. This network only contains attribution that relates directly to a subject such as “ENEL” that is short for “English elective.” This aids the network in displaying subject connections, professors' connections to subjects, and the meaning of these attributions for American Studies. After gather this information, the professors and attributions were added into a spreadsheet titled edges to be imported into RStudio.
 
Following this, I went to the university’s directory and gathered information on each professor that I came across for that time period. I gathered their names, listed titles, type of professorship, and gender. Like the professors and attributions, this data was added into a spreadsheet titled nodes along with individual labels of attributes. This aided in creating additional networks that aided in further answering my questions on professorship and gender dynamics in the program.  

# ***Findings and Results***

To begin explaining my findings and results, I will first address numerical findings from the networks. Then, I will address several network graphs that give a deeper understanding and provide more complete answers for my questions about the American Studies program. The network contained 13 professors: Laura Browder, Patricia Elizabeth Herrera, Nicole Jacqueline Maurantonio, Nicole Sackley, Melissa D. Ooten, Eric S. Yellin, Douglas Leo Winiarski, Lazaro Lima, Glyn Hughes, Bertram D. Ashe, Monika Barbara Siebert, Lauren Craig Tilton, and Edward L. Ayers. These professors taught classes that together covered 20 attributes: AMER, EDSL, ENEL, FLMB, FSHT, FSLT, FSVP, HIAL, HIEL, HIUS, ISAH, ISPD, JWSC, REEL, RHCS, SOEL, THEL, WGHP, WGKP, and WGSS. Each professor had a different title (for example there was a department chair) and interestingly some professors did not have titles indicated on their directory pages. For those, there was only affiliations with programs or departments listed. 

There were three types of professors found: Associate Professor, Asistant Professor, and Professor. Like before, there were also a small number that chose to not describe their occupation. There were three genders represented in the data: she, he, they. With these components, I was able to see connections in the American Studies department by looking at degree, eigen, close, between, cluster, component, component size, gender pronouns, type of prof and title, and type of professor.

**Degree**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/degree.PNG)

Weingart writes that "A node’s degree is, simply, how many edges it is connected to. Generally, this also correlates to how many neighbors a node has, where a node’s neighborhood is those other nodes connected directly to it by an edge" (Weingart-JDH-2011). In relevance to this network, the degree will show which professors have taught the most varying subjects in American Studies and display which attributes are most connected or related. Unsurprisingly, the node with the highest degree is AMER (American Studies) indicated in yellow. This makes sense given that almost all courses in the American Studies program are given the AMER attribute. However, the revealing information comes from the green and lighter blue nodes near the center of the network. The three green nodes are: Nicole Sackley (degree 12), Laura Browder (degree 13), and Patricia Herrera (13).  The light blue node is: THEL that stands for 'Theatre elective' (degree 9). This reveals that Laura Browder and Patricia Herrera teach the most varied attributed courses for the major. Because of this, as seen below, they both have higher influence on the programs subject components. 

**Eigen**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/eigen.PNG)

The Eigen is a measure of influence of nodes in the network and is done by a score assigning algorithm. These numbers reveal what professors are more involved and have more influence in the American Studies program. For instance, Dr. Herrera has a score of 0.58 rounded to the second digit. Where as, Monika Siebeit has a score of 0.01 rounded to the second digit. Dr. Herrera's score is closer to the eigen score 1 meaning she has more influence than Dr. Siebeit. 

**Close**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/close.PNG)

**Between**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/between.PNG)

**Cluster**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/cluster.PNG)

**Component**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/component.PNG)

**Component Size**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/component%20size.PNG)

**Gender Pronouns**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/gender.PNG)

 more female then male professors and only one that identified as both male and female (so outside binary). 

**Type of Professor and Title**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/type%20of%20professor%20and%20title.PNG)

**Type of Professor**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/type%20of%20professor.PNG)

talk abut how 5 and 5 are associate or full prof. Only 1 assistant. 2 not listed.  (no adjucts though richmond does have adjuct professors such as in the journalism department and no visiting professors though ur has some like in the german and political science department )

# ***Limitations and Possibilities***

- the networks could not capture the frequency of some of the subjects and the course of what years some subjects were taught more. It could not account for when a professor came in and if a professor taught more courses in the same time frame (a year or semester) as another professor - making it more frequent or higher ratio of classes taught. It does not show time well and cannot show the changes over time. Data not perfect as attributes can change for the university and are not always uniform year to year. cite time issue here. cite one other type or just such limitations to talk about. write something on possibility - use to diversive program or refine it - use for other reasons 
