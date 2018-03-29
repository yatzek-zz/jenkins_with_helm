
To install:

        helm install --name jenkins --namespace jenkins -f jenkins-values.yaml stable/jenkins

To delete:

        helm del --purge jenkins
