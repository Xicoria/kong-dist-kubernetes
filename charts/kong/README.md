Usage
==========

Note: Make sure helm: [docs here](https://docs.helm.sh/using_helm/#quickstart-guide)
is installed and initialized

1. Clone the repository
2. cd ./charts/kong/
3. edit the "values.yaml" doc to fit your environment
3. helm package .
4. helm install kong-0.1.1.tgz --name your_release_name

You will then see notes on how to connect and use your Kong deployment.

