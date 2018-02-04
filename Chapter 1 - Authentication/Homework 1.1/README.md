# Homework 1.1: Enable SCRAM-SHA-1

### Goal

For this exercise we want you to perform the following set of tasks:
- Launch mongod with no authentication enabled;
- Create user alice with password secret on admin database and role root;
- Relaunch mongod with authentication enabled;
- Run command:
```sh
> db.runCommand({getParameter: 1, authenticationMechanisms: 1})
```

Which of the following statements will successfully run the above command on the standalone server that you've set up?

### Solution


