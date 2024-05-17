# kubectl-ai

NAME | PROMPT | DESCRIPTION | EXAMPLE |
| --- | -------- | ----------- | --------|
app.yaml | kubectl apply -f app.yaml | basic pod manifest |  [app.yaml](https://github.com/Andy-Well/kubectl-ai/blob/40d6200a33d9162388758cf83ae43575a64135f5/yaml/app.yaml) |
app-livenessProbe.yaml | kubectl apply -f app-livenessProbe.yaml | basic pod manifest with liveness probe|  [app-livenessProbe.yaml](https://github.com/Andy-Well/kubectl-ai/blob/71ca5d01310aa2beb2af6df8149fc7894b84ae91/yaml/app-livenessProbe.yaml) |
app-readinessProbe.yaml | kubectl apply -f app-readinessProbe.yaml | basic pod manifest with readiness probe|  [app-readinessProbe.yaml](https://github.com/Andy-Well/kubectl-ai/blob/4b81a0408721cae8b8a0352ac2aefd2935a5120a/yaml/app-readinessProbe.yaml) |
app-volumeMounts.yaml | kubectl apply -f app-volumeMounts.yaml | basic pod manifest with volumeMounts |  [app-volumeMounts.yaml](https://github.com/Andy-Well/kubectl-ai/blob/4b81a0408721cae8b8a0352ac2aefd2935a5120a/yaml/app-readinessProbe.yaml) |
app-cronjob.yaml | kubectl apply -f app-cronjob.yaml | basic cron job manifest manifest |  [app-cronjob.yaml](https://github.com/Andy-Well/kubectl-ai/blob/38900c5339c642f75043147d7936fc885aba7d39/yaml/app-cronjob.yaml) |
app-job.yaml | kubectl apply -f app-job.yaml | basic job manifest |  [app-job.yaml](https://github.com/Andy-Well/kubectl-ai/blob/177624dc16938e1b5505b0f4396e85a3515ac262/yaml/app-job.yaml) |
app-multicontainer.yaml | kubectl apply -f app-multicontainer.yaml | basic multi container pod manifest |  [app-multicontainer.yaml](https://github.com/Andy-Well/kubectl-ai/blob/45fc61e55150daa4a1c88307887bb6ad10ed42f1/yaml/app-multicontainer.yaml) |
app-resources.yaml | kubectl apply -f app-resources.yaml| basic pod with resources manifest |  [app-resources.yaml](https://github.com/Andy-Well/kubectl-ai/blob/45fc61e55150daa4a1c88307887bb6ad10ed42f1/yaml/app-resources.yaml) |
app-secret-env.yaml | kubectl apply -f app-secret-env.yaml | basic pod with secret env manifest |  [app-secret-env.yaml](https://github.com/Andy-Well/kubectl-ai/blob/0283230f6a1c02f61d771a1c48bd5f82dae33eae/yaml/app-secret-env.yaml) |
