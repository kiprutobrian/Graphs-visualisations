# Prepare Your Data at First
Before you make a frequency distribution table in Excel, you have to prepare your data in the following ways:

1. You can use Excel MIN () and MAX () functions to find out the lowest and highest value respectively. Or you can use Excel features: Sort Smallest to Largest, Sort Largest to Smallest or Sort to sort data and then find out the smallest and largest values from a data set. I prefer you to use MIN () and MAX ().  These two will not change your data arrangement.

2. Then decide how many bins you want to create. 

3. Bin size will depend on how many bins you want to create. Your bin size will be: (Highest value – Lowest value)/Bin Size = (252-23)/10=22.9. 22.9 or 23 is not a good bin size. I make it 25.

4. Now time to decide where from you will start your Bins. [if you use FreqGen Excel template, you don’t have to worry about creating these bins manually, the template creates these bins for you automatically.]

5. In Frequency () function there is a parameter bins_array. To find that bins_array you have to use the highest value the bins. 

# 1. Use My FreqGen Excel Template to build a histogram automatically
In four steps you can make a frequency distribution table. The steps are

1 Enter the numbers into any column say B,

2 Enter the number of bins that you want to create,

3 Enter the perfect bin size and

4 Enter the starting number.

When you will finish inserting all these values, you will get your frequency distribution table on the right side of the template. The table includes:

1 The list of bins,

2 The bins_array [bins_array is a parameter of Excel FREQUENCY () function],

3 The frequencies and

4 The cumulative frequencies.

# 2. Frequency Distribution Table Using Pivot Table
Creating a pivot table using this table is simple:

Inserting Pivot Table

Select any cell within the table. Click on the Insert tab → In the Tables group of commands choose PivotTable command → 

Create PivotTable dialog box appears.

In the Create PivotTable dialog box, the table name (in our case it is Table13) is selected under Choose the data that you want to analyze. So our PivotTable will analyze the data of Table13.

Under Choose where you want the PivotTable report to be placed, I select Existing Worksheet and I set Sheet2!$F$2 as the Location of the PivotTable report. 
