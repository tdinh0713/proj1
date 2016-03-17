# Q0: Why is this error being thrown?
There is no Pokemon model of controller yet.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
It's getting chosen from a pre-set list of pokemon with a randomly generated level. It is included along with the seed.rb file.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
It makes a button with the string "Throw a Pokeball!" and sends a patch request to set the pokemon's trainer's id to the current user. The specific line passes in the pokemon's ID to follow as its path.

# Question 3: What would you name your own Pokemon?
Pepe

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
It redirects to the current trainer's page and it takes in a trainer's id to find which trainer's page to go to.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
It checks if there's an error, and grabs the error message associated with it and displays it. It should only happen if there was an error.

# Give us feedback on the project and decal below!
Overall, I thought the project was a good start to putting together everything we learned so far. The topic was exciting because who doesn't love pokemon and it was the perfect amount of work. The extra credit is a nice touch because I'll definitely attempt it when more time opens up (spring break), but am glad it wasn't required as part of the project.

# Extra credit: Link your Heroku deployed app
