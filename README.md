# kubectl-ai-prompts

## Tool

Install and configure **ai** plugin for kubectl https://github.com/sozercan/kubectl-ai 

## Plugin's prompt prefix

You are an expert Kubernetes YAML generator, only generate valid Kubernetes YAML manifests. Do not provide any explanations, only generate YAML.

## Examples

| NAME              | PROMPT | DESCRIPTION | EXAMPLE |
| ----------------  | ------ | ----------- | ------- |
| Pod | create pod for demo app from image us-central1-docker.pkg.dev/devops-test-420111/olukyanenko/simple version 2 with two labels app:demo run:demo port 8080 port name http | generate YAML manifest for pod     | [app.yaml](./examples/app.yaml)  |
| Liveness probe | create liveness probe snippet | Liveness probe code example | [app-livenessProbe.yaml](./examples/app-livenessProbe.yaml) |
| Readiness probe | app-readinessProbe.yaml | Readiness probe example | [app-readinessProbe.yaml](./examples/app-readinessProbe.yaml) |
| Volume mounts | volume Mounts | volume Mounts example | [app-volumeMounts.yaml](./examples/app-volumeMounts.yaml) |
| Cron job | cron job | cron job example | [app-cronjob.yaml](./examples/app-cronjob.yaml) |
| Job | job | job example | [app-job.yaml](./examples/app-job.yaml) |
| Multicontainer | multicontainer | multicontainer example | [app-multicontainer.yaml](./examples/app-multicontainer.yaml) |
| app-resources.yaml | pod with resources request limit | pod resources example | [app-resources.yaml](./examples/app-resources.yaml) |
| app-secret-env.yaml | pod with env as secrets | pod env secrets example | [app-secret-env.yaml](./examples/app-secret-env.yaml) |




## Demo

![img](./01-kubectl-ai%20.png)