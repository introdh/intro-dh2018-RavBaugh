 **Raven Baugh**

 **Assignment 2: Network of American Studies Program**



# ***Introduction***


What are the components of the American Studies program at the University of Richmond? Why is it called ‘Studies’ rather than a more specific subject area? Who are the core faculty for the American Studies program? These are some of many questions I considered before building my network assignment. M. E. J. Newman states that “a network is, in its simplest form, a collection of points joined together in pairs by lines” (Newman-*Networks: An Introduction*- 2010). These lines create interlocking systems that map interdependency and relationships (Weingart-JDH-2011).This is helpful to display relationships between subjects and to convey patterns of connection between various items. For networks, the subjects are the nodes and the connections are the edges that together create a larger interlocking system (Newman-*Networks: An Introduction*- 2010). 


# ***Process***


Firstly, I want to address why I selected this network and then explain my process for collecting data. I decided to create a network on American Studies as I wanted more insight on the connections between individuals, gender, and subjects that make up the interdisciplinary program. This would also reveal how diverse, in regards to subject matter and gender, that the program is. I selected my data from the University of Richmond’s bannerweb site. There, I went into the class listings for American Studies from Fall 2015 to Spring 2019. This gave me four academic years of data to create my network. This time frame allowed for more subjects and professors to be listed that taught in this program. 

 I decided to select the professors and the attributes from each course listing. I did this because it is important to consider the professors teaching the courses as each professor has a different expertise or specialized knowledge that can be applied to a class. As for attributes, attribution is the method that the university uses to assign four letter identifiers to courses to readily conveywhat subjects or programs are within a course. This network only contains attribution that relates directly to a subject such as “ENEL” that is short for “English elective.” This aids the network in displaying subject connections, professors' connections to subjects, and the meaning of these attributions for American Studies. After gather this information, the professors and attributions were added into a spreadsheet titled edges to be imported into RStudio.
 
Following this, I went to the university’s directory and gathered information on each professor that I came across for that time period. I gathered their names, listed titles, type of professorship, and gender. Like the professors and attributions, this data was added into a spreadsheet titled nodes along with individual labels of attributes. This aided in creating additional networks that aided in further answering my questions on professorship and gender dynamics in the program.  

# ***Findings and Results***

To begin, I will first address numerical findings from the networks. The network contained 13 professors: Laura Browder, Patricia Elizabeth Herrera, Nicole Jacqueline Maurantonio, Nicole Sackley, Melissa D. Ooten, Eric S. Yellin, Douglas Leo Winiarski, Lazaro Lima, Glyn Hughes, Bertram D. Ashe, Monika Barbara Siebert, Lauren Craig Tilton, and Edward L. Ayers. These professors taught classes that together covered 20 attributes: AMER, EDSL, ENEL, FLMB, FSHT, FSLT, FSVP, HIAL, HIEL, HIUS, ISAH, ISPD, JWSC, REEL, RHCS, SOEL, THEL, WGHP, WGKP, and WGSS. Each professor had a different title (for example there was a department chair) and interestingly some professors did not have titles indicated on their directory pages. For those, there were only affiliations with programs or departments listed. 

There were three types of professors found: Associate Professor, Asistant Professor, and Professor. Like before, there were also a small number that did not identify their level of professorship. There were three genders represented in the data: she, he, they. With these components, I was able to see connections in the American Studies department by looking at degree, eigen, close, between, cluster, gender pronouns, type of prof and title, and type of professor.

**Degree**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/degree.PNG)

Weingart writes that "A node’s degree is, simply, how many edges it is connected to. Generally, this also correlates to how many neighbors a node has, where a node’s neighborhood is those other nodes connected directly to it by an edge" (Weingart-JDH-2011). In relevance to this network, the degree will show which professors have taught the most varying subjects in American Studies and display which attributes are most connected or related. Unsurprisingly, the node with the highest degree is AMER (American Studies) in yellow. This makes sense given that almost all courses in the American Studies program are given the AMER attribute. However, the revealing information comes from the green and lighter blue nodes near the center of the network. The three green nodes are: Nicole Sackley (degree 12), Laura Browder (degree 13), and Patricia Herrera (13).  The light blue node is: THEL that stands for 'Theatre elective' (degree 9). This reveals that Laura Browder and Patricia Herrera teach the most varied attributed courses for the major. Because of this, as seen below, they both have higher influence on the programs subject components. 

**Eigen**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/eigen.PNG)

The Eigen is a measure of influence of nodes in the network and is done by a score assigning algorithm. These numbers reveal what professors involve and have more influence in the American Studies program. For instance, Dr. Herrera has a score of 0.58 rounded to the second decimal point. Where as, Monika Siebeit has a score of 0.01 rounded. Dr. Herrera's score is closer to the eigen score 1 meaning she has more influence than Dr. Siebeit. 

**Close**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/close.PNG)

Close measures the distance between, or 'how close,' nodes are to other nodes. Centrality shows how important a node is for the network (Weingart-JDH-2011). For example, the node FSLT (Literary Studies) is dark purple on the network with a close score of 0.00 rounded to the second decimal point. This means that Literary Studies is not close to most other subjects or individuals on the network. This shows that American Studies has more central themes that make up the program. 

**Between**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/between.PNG)

Like close, between measures centrality; however, it measures by finding the shortest paths. For this particular network, the between measurement shows similar information to the close measurement. 

**Cluster**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/cluster.PNG)

The cluster network displays the communities and are greated by closely cited nodes. This network answers one of my questions about the dynamics of attribution and American Studies. Cluster 1, located on the bottom left of the network, shows a linkage between RHCS (Rhetoric and Communications) and WGSS (Women, Gender and Sexuality Studies). The algorithm has created a community with not only these subjects but also the professors that teach in these departments: Dr. Melissa Ooten, Dr. Lauren Tilton, and Dr. Nicole Maurantonio. This explains that not only is WGSS and RHCS vital to the American Studies major, but Professors from both departments teaching these subjects is common for the program. 

**Gender Pronouns**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/gender.PNG)

 The additional networks reveal tlling details about the American Studies program. For example, there were three genders represented for professors; however, only one person identified outside of the binary. There are also more females than males that teach in American Studies. This speaks to the diversity of faculty allowed to teach in the program and how that influences how American Studies is learned at the university.  

**Type of Professor and Title**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/type%20of%20professor%20and%20title.PNG)

The type of Professor and Title is important to note as the networks reveal that a professor's department does not prevent them from teaching across fields. For example, Dr. Tilton is listed under the Rhetoric and Communications Department; however, she teaches courses for both WGSS and FSHT (Historical Studies). This aids in making American Studies an interdisciplinary program and explaining why certain professors with varied specialized knowledge teach in the program. 

**Type of Professor**

![alt text](https://github.com/introdh/intro-dh2018-RavBaugh/blob/master/images/type%20of%20professor.PNG)

Finally, the type of professor reveals barriers of entry for the major and possible restrictions for faculty. The network shows that there are five professors, five associate professors, one assistant professor, and two non-identifying professors. This shows that most faculty are of higher level professorship that are allowed to teach in the program. By doing this, it shows that American Studies may be limited in faculty who can teach or who are allowed in the program. For instance, there are no adjuct or visiting professors in the program at all; however, these types of professors can be found in other programs such as Global Studies. 

# ***Limitations and Possibilities***

There were several limitations with this network due to the nature of networks and due to my dataset. Firstly, I was limited in how large I could make my data set due to time constraints and the limited size of graphs. When a network has several intersections, nodes, and lines it can become confusing for the viewer to see. This can make it difficult to explain and present as well as comprehend (Newman-*Networks: An Introduction*- 2010). Another limitation was that this RStudio program does not add weights to the data. Due to this, I cannot view how much certain professors correlate to attributes  (Weingart-JDH-2011). Finally, I cannot view the attributes over time and the change in the American Studies program. I cannot see if newer professors are teaching at the same frequency as older professors when they joined the program. 

Even though there are limitations, I find that this network can be beneficial for the University of Richmond. For starters, it can display what subjects are in American Studies and can be compared to other interdisciplinary programs. Like many networks, this can be a starting point on discussions of the gender makeup and gender diversity for programs and departments on campus. I also think the data set opens a question about the power dynamics of professorship levels and why certain professors can and cannot teach in fields. 

