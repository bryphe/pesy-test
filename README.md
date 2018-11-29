# pesy-test


[![CircleCI](https://circleci.com/gh/yourgithubhandle/pesy-test/tree/master.svg?style=svg)](https://circleci.com/gh/yourgithubhandle/pesy-test/tree/master)


**Contains the following libraries and executables:**

```
pesy-test@0.0.0
│
├─test/
│   name:    TestPesyTest.exe
│   main:    TestPesyTest
│   require: pesy-test.lib
│
├─library/
│   library name: pesy-test.lib
│   namespace:    PesyTest
│   require:
│
└─executable/
    name:    PesyTestApp.exe
    main:    PesyTestApp
    require: pesy-test.lib
```

## Developing:

```
npm install -g esy
git clone <this-repo>
esy install
esy build
```

## Running Binary:

After building the project, you can run the main binary that is produced.

```
esy x PesyTestApp.exe 
```

## Running Tests:

```
# Runs the "test" command in `package.json`.
esy test
```
