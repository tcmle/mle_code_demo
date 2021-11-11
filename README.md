# mle_code_demo
A demo GitHub repository for MLOps with necessary Python scaffolding using a Makefile, linting, and testing.

### To use this demo roject

Create a virtualenv

""" python3 -m venv ~/.your-repo-name """

Source virtualenv to “activate” it:

""" source ~/.your-repo-name/bin/activate """

The Python scaffolding’s final step is: 
*add a source code file and a test file. 
**  source code called hello.py
** test file test_hello.py using pytest framework

### Configuring Continuous Integration

implement continuous integration for this project with GitHub Actions
*** create a file inside of project directories: .github/workflows/<yourfilename>.yml