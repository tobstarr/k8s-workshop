# jenkins

	gcloud compute disks create jenkins --size 50GB
	kubectl apply -f jenkins.dpl.yml
	kubectl apply -f jenkins.svc.yml

	kubectl -n kube-system get pods
	kubectl -n kube-system port-forward <jenkins_pod_name> 0:8080

# registry

	gcloud compute disks create registry --size 50GB
	kubectl apply -f registry.dpl.yml
	kubectl apply -f registry.svc.yml
