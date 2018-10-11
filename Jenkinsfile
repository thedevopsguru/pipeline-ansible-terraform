pipeline {
stage ('Ansible Playbook run') {
                ansiblePlaybook(
                    inventory: '/etc/ansible/hosts',
                    installation: 'Deploy the terraform bucket using Ansible',
                    playbook: '/home/ec2-user/run_ansible.yml',
                    extras: '--private-key="/home/ec2-user/devops.pem"','aws_s3_bucket': ${aws_s3_bucket}'
					
					
                )
            }
			
	}
