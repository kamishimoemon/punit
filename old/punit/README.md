# A puny PHP testing framework

A test is just a function that returns a boolean. `true` means that the test passed, `false` failed. Put all your tests inside
a `/test` directory... and that's it.

A test is any function that fulfills one of the following requirements:
 - it's name starts with the word "test" and accepts no arguments
 - declares the @test annotation in it's doccomment and accepts no arguments

All tests must return some value that indicates if the test has passed or failed.

Valid return types:
 - boolean: `true` means success, `false` means failure
 - string: a string is always interpreted as a failure message
 - throws exception: test failed (obviously)
 - anything else: test failed

## Roadmap

[Visitar tablero de Trello](https://trello.com/b/TK1XJiOS)