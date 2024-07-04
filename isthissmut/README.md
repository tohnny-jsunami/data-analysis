# Project Idea
## isthissmut.com

### Concept	
user input book title or isbn of a book, 
	returns "is this book smut? yes/no"

### Data Needed
	
* list of books that are smut
	
### Logic
	
if user inputs a book title or isbn matching a book on the list (true), returns "Yes"
	
else returns "No"

### Challanges
* where to get the data?
	* ~~bcheck kaggle?~~
	* goodreads api!
		* can use `search.books`

* how to use goodreads api?

* how to host
	can host notebooks on kaggle.com
	can use ipywidgets to get interactive buttons

### Steps
1. get data
	* maybe use test data of already publish good reads list from kaggle
	* might have to manually compile smut list 
	* or learn how to scrape data out of good read

2. build code
	* make new branch and folder, start prototype in jupyter notebooks
	* start with `input`
	* read in data
	* function to ask for user data

3. build interactivity
	* experiment with widgets to make the notebook more interactive
	

