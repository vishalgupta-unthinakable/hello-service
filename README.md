# hello-service

Demo app showing the multi-app GitOps pipeline — second app onboarded onto the same automation as `my-docker-app`.

## Deployment

`git push` → CI builds and pushes image → manifest repo gets bumped → ArgoCD syncs → live at NodePort `30081`.

See onboarding docs in the [manifest repo README](https://github.com/vishalgupta-unthinakable/my-k8s-app#onboarding-a-new-app).
