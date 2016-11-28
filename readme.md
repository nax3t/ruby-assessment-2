# Ruby Assessment #2

1. Convert the following string to a float: `"7.65"`
2. Calculate the length of this string: `"supercalifragilisticexpialidocious"`
3. Given the following code, what will **b** return?

	```ruby
	a = "hello"
	b = a
	a = "good bye"
	```
4. Iterate over the following array and print each item in all caps:

	`["can", "you", "hear", "me", "now"]`
5. Using concatenation, print the first name, last name, and city from the following hash in sequence (e.g., "Bob Ross - Daytona Beach, FL"):

	```ruby
	contact = { 
		first_name: "Bob",
		last_name: "Ross",
		city: "Daytona Beach, FL" 
	}
	```
6. Repeat the previous question, but this time use string interpolation instead of concatenation
7. Write a method that takes a string and reverses it, then prints it 3 times with an exclamation at the end, e.g., reverse_repeat("hello") => olleh! olleh! olleh!
8. Write an Animal class that, when instantiated, creates a new animal with a name, age, and type
9. Write a Kitten class that inherits from Animal class, inherits all of it's properties and adds another property of breed
10. Add an instance method to the Kitten class named **sound** that will print "Purrr" when called