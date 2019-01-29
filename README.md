# Market-_Basket_Analysis_Course_Outline
Course Outline – Market Basket Analysis in Python

## Chapter 1 – Introduction to Market Basket Analysis
  * Lesson 1.1 – What is Market Basket Analysis?
      * A learning objective: Define what is a market basket analysis & why we use it. Highlight the approach of filtering datasets & making better recommendations. Define the metrics we will use to determine whether a relationship exists or not. This should cover the topic of Support, Confidence & Lift. All of which are the backbone in our calculations.
* Lesson 1.2 – Calculating the metrics
  * A learning objective: Students will be able to define their own function that calculates support, confidence, & lift. This gives us insight as to how the packages we will use are working behind the scenes.
* Lesson 1.3 – Working with Pandas
  * A learning objective: Students will see the different ways to load data into pandas using the read_csv & read_excel methods. Along with this we will see the different ways to easily select and manipulate data in Pandas.
    
## Chapter 2 – Case Study – Online Retail Sales
* Lesson 2.1 – Discussing the Data Set & Defining the Objectives
  * A learning objective: Discuss the data set layout and cover the main sequences of events that will do in this analysis.
* Lesson 2.2 – Loading the Data Set into Pandas & Transforming the Data
  * A learning objective: Use the read_excel() to load data into Pandas. Use the dropna() to remove unnecessary columns & str.contains to remove credit transactions. Use the Plt.Hist() to create a histogram that shows the number of orders by customer.
* Lesson 2.3 – Preparing the Data
  * A learning objective: Create a basket of items using the groupby(), Sum(), & set_index(). Create a custom function that we can apply across our data frame & then use the applymap() to apply function.
* Lesson 2.4 – Performing Analysis Using Apriori
  * A learning objective: Use the mlExtend apriori() library to build a frequent item list. Use the mlExtend association_rules() to define association rules in the analysis. Define Lift & Confidence thresholds that we will apply.
* Lesson 2.5 – Compare Items to Find Opportunity.
  * A learning objective: Compare items that our bought together to see how sales come out. This means seeing if items that our bought together have the same level of sales.
  
## Chapter 3 – Case Study – Bakery Sales
* Lesson 3.1 – Discussing the Data Set & Defining the Objectives
  * A learning objective: Discuss the data set layout and cover the main sequences of events that will do in this analysis.
* Lesson 3.2 – Loading the Data Set into Pandas & Transforming the Data
  * A learning objective: Use Panda’s Read_CSV to load dataset into data frame. Discussing column headers parameters. Remove the transactions that contain none using drop() & count the number of transactions for each group using value_counts().
* Lesson 3.3 – Visualize Data.
  * A learning objective: Create a bar chart using plt.subplots() to see data by different time frames. This will include by the different categories of items and by the time they were purchased.
* Lesson 3.4 – Prepare Data for Analysis. 
  * A learning objective: Using pivot_table() we will create a table of all the transaction. This will give us an idea of what items we want to see sell the best. Students will use the TransactionEncoder() to define an encoder and apply it across their data frame.
* Lesson 3.5 – Define Rules & apply them across our data.
  * A learning objective: Use mlExtend association_rules() to define association rules in the analysis. Then apply those rules across the antecedents & consequents columns using a lambda function. Filter the data to reflect the highest selling item.

## Chapter 4 – Case Study – Creating A Graph Network
* Lesson 4.1 – Why Graphs Make Sense for Market Basket Analysis
  * A learning objective: Understanding the advantages of why using graphs make sense when it comes to showing relationships.
* Lesson 4.2 – Defining Our Graph Function
  * A learning objective: Use the nx.Graph() class to create a new graph object that we can then add edges & nodes to. Create a list of Edges & Nodes using for loops & the .edges() & .adjacency() methods.
* Lesson 4.3 – Creating a Kamada Kawai Graph
  * A learning objective: Use the draw_kamada_graph() to create force-directed graph.
* Lesson 4.4 – Creating a Circular Network Graph & Spring Network Graph
  *A learning objective: Use the draw_circular() to create a circular refence  and use the draw_spring() to create a graph with a spring layout.
