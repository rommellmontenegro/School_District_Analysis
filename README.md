# School_District_Analysis

Overview of the school district analysis
This exercise allowed us to use Jupyter to perform a series of cool python coding across different levels of analysis. A new method, loc, was central to getting started on this exercise. It can efficiently replace data with ‘NaN’ within a dataframe. 

This entire module really focused on how dataframes allows for creative coding functionality. The following kinds of analysis functionality was demonstrated via dataframes in this module: reading cvs files into a dataframe, merging of data, deletion, search and replacement of strings/falsified data, raw data level calculations, aggregated data calculations, manipulation of data, formatting of columns, counting of rows/certain data values, creation of new data values via mathematical conditional functions.

Dataframes also provide a great way of changing its structure like one would in a table or a matrix. Adding, removing, moving, creating, new columns of data was demonstrated. A dataframe’s sorting across rows functionality was also explored.

Results
* How is the district summary affected?
	The percentage of % Overall Passing, % Passing Reading, and %Passing Math each dropped 1 percentage point.
* How is the school summary affected?
	Thomas High School’s academic performance fell across all metrics, but the following shifted percentage points: 	% Passing Math: -26%, % Passing Reading: -28%, and % Overall Passing: -26%.
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
	It is no longer in the top five highest performing schools.
* How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade: A NaN is now reported for Thomas High School’s 9th grade class for reading and math scores in their respective tables.
    * Scores by school spending: For the $630 to $644 spending range, the % Passing Math dropped 7%, % Passing Reading dropped 7%, and % Overall Passing dropped 6%.
    * Scores by school size: For the Medium (1000-2000) school size range, the % Passing Math dropped 5%, % Passing Reading dropped 6%, and % Overall Passing dropped 5%.
    * Scores by school type: For charter schools, the % Passing Math dropped 3%, % Passing Reading dropped 3%, and % Overall Passing dropped 3%.
    * Please see images in repository.

Summary
The omission of the falsified math and reading scores from Thomas High School shifted the scores reported by grade, school spending levels, school size and school type since the previous scores reported for ninth graders at Thomas High School were much higher than they should have been originally. These higher scores had inflated the higher level calculations.
