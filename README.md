# arrays
Sinatra app to work with arrays

## To start the homework application:

1. Open the terminal/cmd line
2. Use the cd command to navigate to the homework application
3. Once in the root, type in "arrays_work.rb" to start the server
4. If the site does not start and tells you to run "bundle install", do so and then repeat the previous site
5. Once the server is running, open your browser to http://localhost:3000

		NOTE: View this page in a browser to read information about completing this assignment


		Example: Create an array with 3 colors:
		<% 
		colors = Array["orange", "blue", "white"]
		%>



		Here are the steps to complete:
		~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

		1. using just one line of code, create a simple array called "years" with a range of years from 1972 - 2013

			Use the "debug" function to print the data structure to the screen. If done properly, the result should look like the following:

		---
		- 1972
		- 1973
		- 1974
		- 1975
		- 1976
		- 1977
		- ..and so on

		<%
			#complete step 1 here
		%>


		2. create an array of states called "states". Should include at least 5 states NOT in alphabetical order.

		<%
			#complete step 2 here
		%>


		3. Use the appropriate array method to sort the states array alphabetically without permanently altering the array
		<% 
			#complete step 2 here 
		%>


		4. Now sort the states array alphabetically so that the sorting is permanent
		<% 
			#complete step 4 here
		%>



		5. Iterate through the states array of states using HTML to display them as an unordered list

		-->

		<h2>State List</h2>

		<p>here is a list of states...</p>

		<!-- iterate through each state in the array and put them into list items individually -->
		<!-- complete step 5 under this comment -->


		<h2>My Array of Years:</h2> 
		<!-- use debug to dump out the years array here -->

	</div>
</div>

<div id="examples">
	<div class="content-padding">
		<h2>Example</h2>
		<!--  this is how you dump out a data structure of any type -->
		<%= debug colors %>
	</div>
</div>



<div id="instructions">
	<div class="content-padding">
		<h3>To complete this assignment:</h3>
		
		<ol>
			<li>Open this file in your text editor (app/views/assignemnts/arrays.html.erb</li>
			<li>Follow the instructions for each step.
				<ul>
					<li>All Ruby code needs to be surrounded by &lt;% ... %></li>
					<li>If the code is writing content (ie,  HTML) to the screen, it needs to be surrounded by &lt;%= ... %></li>
					<li>To dump out the first array use the debug feature. &lt;%=debug my_var %></li>
				</ul>
			</li>
			<li>Complete the remaining steps</li>
			<li>When looping through the array of states for the final step, you will use &lt;%= %> and &lt;%= %>. 
			</li>
		

			<li>Once you have completed all steps and are ready to turn the assignment in:
				<ol>
					<li>Copy this file from "views/assignments" to "views/completed"</li>
					<li>Make sure you add the files to your svn working copy</li>
					<li>Commit your work (to the trunk)</li>
					<li>Tag your current progress as "arrays-assignment"</li>
					<li>To confirm, go to https://itmlab-web.business.nd.edu/svn/mgti-40660-fa13/students/your_netid/ and browse your repo. The entire homework application should be in the tags folder with the tag name.
				</ol>
			</li>
		</ol>

		<p class="note"><span class="shout">Note:</span> Before turning the assignment in, run "rails s" from the command line, click the "Arrays" under completed files and make sure there are no errors.</p>
	</div>
</div>
