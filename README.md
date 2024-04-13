# kubectl-ai-prompts

## Tool

Install and configure **ai** plugin for kubectl https://github.com/sozercan/kubectl-ai 

## Plugin's prompt prefix

You are an expert Kubernetes YAML generator, only generate valid Kubernetes YAML manifests. Do not provide any explanations, only generate YAML.

## Examples

| NAME              | PROMPT | DESCRIPTION | EXAMPLE |
| ----------------  | ------ | ----------- | ------- |
| Pod        | create pod for demo app from image us-central1-docker.pkg.dev/devops-test-420111/olukyanenko/simple version 2 with two labels app:demo run:demo port 8080 port name http | generate YAML manifest for pod     |   |
| SQL Hat           |   True | 23.99       | ------- |
| Codecademy Tee    |  False | 19.99       | ------- |
| Codecademy Hoodie |  False | 42.99       | ------- |



## Demo

![img](./01-kubectl-ai%20.png)