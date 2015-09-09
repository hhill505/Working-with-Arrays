# Arrays
Sinatra app to work with arrays

## To get started

1. Open the terminal/Command line tool can navigate to where you want the files to reside
2. Clone this repository
3. If you haven't, run the following
		gem install sinatra
		gem install rerun
4. run **ruby run.rb** or **rerun 'ruby run.rb'**


## To start the homework application:

1. Open the terminal/cmd line
2. Use the cd command to navigate to the homework application
3. Once in the root, type in "arrays_work.rb" to start the server
4. If the site does not start and tells you to run "bundle install", do so and then repeat the previous site
5. Once the server is running, open your browser to http://localhost:4567

## Here are the steps to complete:

### Years 
1. Find the 'get /years' in the run.rb file

	get '/years' do
	  # code!
	  erb :years, layout: :main
	end

2. Using just one line of code, create a simple array called "years" with a range of years from 1972 - 2013

3. Find states.erb file in the views folder and dump out the contents of the years variable

### States
4. Find the 'get /states' block in the run.rb file

	get '/stats' do
	  # code!
	  erb :states, layout: :main
	end

5. Create an array of states called "states". Should include at least 5 states NOT in alphabetical order.

6. Use the appropriate array method to sort the states array alphabetically without permanently altering the array

7. Now sort the states array alphabetically so that the sorting is permanent

8. Find the states.erb file in the views folder and iterate through the states array of states using HTML to display them as an unordered list
