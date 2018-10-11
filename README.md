# pipeline-ansible-terraform
This is used to deploy terraform resources using playbook &amp; jenkinsfile

Step 1:-
Create pipeline in Jenkins, create stage for ansible.Pass all the files and variables in the paramater.
Run pipeline job and it will execute the step defined in Jenkinsfile. 
Step 2:-
Pass the terraform input variables from the ansible.

Step 3:-
Inside the yml define the terraform resource for s3 bucket creation.

Step 4:-
terraform plan & terraform init in the ansible playbook so that user can create the resources as per the plan later on.

Step 5:--
Verify the plan in console.

We can customize it in many ways to perform the terraform deployments using ansible playbook.

