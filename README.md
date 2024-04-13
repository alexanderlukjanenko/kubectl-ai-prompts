# kubectl-ai-prompts

## Tool

Install and configure **ai** plugin for kubectl https://github.com/sozercan/kubectl-ai 

## Plugin's prompt prefix

You are an expert Kubernetes YAML generator, only generate valid Kubernetes YAML manifests. Do not provide any explanations, only generate YAML.

## Examples

| NAME              | PROMPT | DESCRIPTION | EXAMPLE |
| ----------------  | ------ | ----------- | ------- |
| Pod | create pod for demo app from image us-central1-docker.pkg.dev/devops-test-420111/olukyanenko/simple version 2 with two labels app:demo run:demo port 8080 port name http | generate YAML manifest for pod     | [app.yaml](./yaml/app.yaml)  |
| Liveness probe | create liveness probe snippet | Liveness probe code example | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml) |
| Readiness probe | app-readinessProbe.yaml | Readiness probe example | [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
| Volume mounts | volume Mounts | volume Mounts example | [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml) |
| Cron job | cron job | cron job example | [app-cronjob.yaml](./yaml/app-cronjob.yaml) |
| Job | job | job example | [app-job.yaml](./yaml/app-job.yaml) |
| Multicontainer | multicontainer | multicontainer example | [app-multicontainer.yaml](./yaml/app-multicontainer.yaml) |
| app-resources.yaml | pod with resources request limit | pod resources example | [app-resources.yaml](./yaml/app-resources.yaml) |
| app-secret-env.yaml | pod with env as secrets | pod env secrets example | [app-secret-env.yaml](./yaml/app-secret-env.yaml) |




## Demo plugin

![img](./01-kubectl-ai%20.png)


## Alternative demo pure AI interface

![img](./02-kubectl-ai%20.png)