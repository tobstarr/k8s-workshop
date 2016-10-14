# jenkins

gcloud compute disks create jenkins --size 50GB
kubectl apply -f jenkins.dpl.yml
kubectl apply -f jenkins.svc.yml
