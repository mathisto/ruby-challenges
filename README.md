# Welcome!
We are so excited you are considering joining our team. Please fork this repo and complete the challenges below. All tasks should be placed into one git repository. Each task should be contained in its own file in its own folder and made as a separate commit. The code should be formatted according to [the Ruby Style Guide](https://github.com/rubocop-hq/ruby-style-guide). All commit messages are should be made using the [following guidlines](https://chris.beams.io/posts/git-commit/)

### Task 1 - API Endpoints
Using only the Ruby Standard Library (no gems), write a method named `users` that takes a single optional argument and makes a HTTP GET request to `https://reqres.in/api/users`. If an `id` is provided as an argument, only retrieve the record with the matching ID. Otherwise, retrieve all records. If an invalid argument is provided, assume all records are desired. Once you have the JSON, convert and write it to a YAML file called `users.yml`. Make sure to include an example YAML file with your commit.

### Task 2 - Basic Cryptography
A string has been passed through three separate encodings in the following order: Original -> SHA-1 -> MD5 -> SHA-256. Write a method that takes this triple encoded string `mystery_string = "C13797461BE51FC3D73F0CEC48876AAEA79BC050BA0438CD6511C11C9421FE75"` and fully decodes it to it's original state. The method should output the fully decoded string to the console. Add the answer as a commented line at the end of your file.

### Task 3 - Unorthodox/Impossible method creation (Advanced level)
Create a method called `ultimate.answer` which takes no arguments. The method should simply return the number `42`, the answer to the ultimate question of life, the universe and everything. Invoke your method and have it print the result to console.
