1.	Why MapReduce program is needed in Pig Programming?
In MapReduce mode, Pig translates queries into MapReduce jobs and runs them on a Hadoop cluster. The cluster may be a pseudo- or fully distributed cluster. MapReduce mode is what you use when you want to run Pig on large datasets.
2.	What are advantages of pig over MapReduce?
•	Decrease in development time. This is the biggest advantage especially considering map-reduce jobs' complexity, time-spent and maintenance of the programs.
•	Learning curve is not steep, anyone who does not know how to write map-reduce or SQL for that matter could pick up and can write map-reduce jobs; not easy to master, though.
•	It is quite effective for unstructured and messy large datasets. Actually, Pig is one of the best tool to make the large unstructured data to structured.
3.	What is pig engine and what is its importance?
It is acts as interpreter between pig latin script and Mapreduce jobs.It creating environment to execute Pig scripts into series of Mapreduce jobs in parallel manner.
4.	What are the modes of Pig execution?
There are two modes in Pig execution
	a)Local mode-To run pig in local mode you need access to a single machine where all files are installed and run using our local host and file system.
	b)Mapreduce mode-To run pig in mapreduce mode ,you need access to a Hadoop Cluster and HDFS installation.Mapreduce mode is the default mode.
        5. What is grunt shell in Pig?
	We could run Pig Scripts only after invoking the Grunt shell.In addition to that certain useful and utility commands provided by the grunt shell.
6.What are the features of Pig Latin language?
•	Rich set of operators
•	Ease of programming
•	Optimization opportunities
•	Extensibility
•	User defined functions
•	Handles all kind of data
7.Is Pig latin commands case sensitive?
The names of relations and fields are case sensitive.The names of Pig latin functions are case sensitive.the names of parameters and all other pig latin words are case insensitive.
Eg:
Function name such as PigStorage and COUNT are case sensitive whereas keywords such as load,using,as,group,by,foreach etc are case insensitive.
8.What is a data flow language?
In dataflow language,you have a stream of data which is passed fro instruction to instruction to be processed.Conditional execution,jumps and procedure calls route the data to different instructions. A dataflow if statement would route the data to the correct branch.
