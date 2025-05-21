1) I would put my automated tests in a Github action that runs whenever code is pushed because that is the whole point of automation testing. If I have to run them manually, it's not automation testing. Running them after all development is completed is pointless because I'd want to test continously as I'm developing my project.

2) I would not use E2E testing to test the output of a function. That is what unit tests are for. E2E testing is to test the front end, and it doesn't seem very practical to test the output of a function using it.

