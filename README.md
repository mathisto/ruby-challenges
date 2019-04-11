# Welcome!
We are so excited you are considering joining our team. Create a repo whose name is the MD5 hash of your first and last name concatenated (i.e. `JohnSnow` -> `0F4DD1CD0109780A797879DD3DD0C700` and complete the challenges below. All tasks should be placed into one git repository. Each task should be contained in its own file and in its own folder and made as a separate commit. The code should be formatted according to [the Ruby Style Guide](https://github.com/rubocop-hq/ruby-style-guide). All commit messages are should be made using the [following guidlines](https://chris.beams.io/posts/git-commit/)

### Task 1 - API Endpoints
Using only the Ruby Standard Library (no gems), write a method named `users` that takes a single optional argument and makes a HTTP GET request to `https://reqres.in/api/users`. If an `id` is provided as an argument, only retrieve the record with the matching ID. Otherwise, retrieve all records. If an invalid argument is provided, assume all records are desired. Once you have the JSON, convert and write it to a YAML file called `users.yml`. Make sure to include an example YAML file with your commit.

### Task 2 - Basic Cryptography
A string has been passed through three separate encryptions in the following order: Original -> Base64 -> AES-256 -> Blowfish -> Final. Write a method that takes this triple encoded string `mystery_string = "OXbVgH7UriGqmRZcqOXUOvJt8Q4JKn5MwD1XP8bg9yHwhssYAKfWE+AMpr25HruA"` and fully unencrypts it to its original state. The method should output the fully decoded string to the console. Add the answer as a commented line at the end of your file.

### Task 3 - Unorthodox/Impossible method creation (Advanced level)
Create a method called `ultimate.answer` which takes no arguments. The method should simply return the number `42`. Invoke your method and have it print the result to console.
