# devops-practice

As part of the DevOps recruting process, it is require to present practical knowledge. Please read carefully the instruction of your pratical test.


# Exercise

Choose an open source project on GitHub, fork the repository and deploy it to AWS.

# Solutions

We will accept any of the following types of solution:

- A script(s) using a CLI, SDK, API or library that deploys the chosen projetct on the AWS cloud.

- A Docker Compose file or another similar container orchestration solution that deploys the chosen projetct on the AWS cloud.

- A recipe using one or more configuration management tools (e.g. Terraform, Ansible, Chef, Puppet, CloudFormation, Vagrant, Packer, etc.) that deploys the chosen projetct on the AWS cloud.

- A pipeline implemented on a Continuous Integration Tools that deploy the chosen project on the AWS cloud.

**IMPORTANT** Your solution must contain step-by-step instructions on how to deploy the chosen project using _your solution_. On your forked repository create a new markdown file named `INSTRUCTIONS.md` with the instructions, feel free to add a short paragraph and/or a diagram to better explain your solution.

# Expectations

When reviewing this exercise, we will take the following points into consideration:

1. Whether the solution works or not (this is eliminatory) 
2. Secrets must not be pushed to remote
3. How easy it is to deploy the solution
4. How resilient it is (e.g. what happens if the deployment fails or will code with errors be deployed?)

We don't expect a production-grade solution, but we expect you to show that you are able to deploy (preferably in an automated manner) code that you didn't write.

# Submission

After you are finished, publish your solution on your forked repository publicaly and send it to us.

