# replace-script

## Assignment in Development & Operations

To install, type these commans starting in your home directory:

```
git clone https://github.com/jamiewendt/replace-script replace-script
cd replace-script && chmod u+x run-test replace
```

To create or remove the test directory:
```
./run-test setup
./run-test teardown
```

To run the replace script:
```
./replace directory oldpattern newpattern

example:
./replace test DevOps WebApp
