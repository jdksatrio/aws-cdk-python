# aws-cdk-python (cloudacademy)

ca-python-app: The top-level folder of your project
.venv/: Python virtual environment configurations
ca_python_app/: The directory that stores your project's stack construct file
ca_python_app_stack.py: Your custom CDK Stack construct file. For this sample app, this is where your SQS queue and SNS topic are defined.
tests/: The sample application provides a directory to store programming language-specific test files
app.py: The application entry point and top-level App construct
cdk.json: The configuration file that defines what executable CDK should run to generate the CDK construct tree
requirements.txt: The file used by pip to manage and install application dependencies. The aws-cdk-lib and constructs dependencies in this file are all you will need to proceed with the lab.
