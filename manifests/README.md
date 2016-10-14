# jenkins

	gcloud compute disks create jenkins --size 50GB
	kubectl apply -f jenkins.dpl.yml
	kubectl apply -f jenkins.svc.yml

	kubectl -n kube-system get pods
	kubectl -n kube-system port-forward <jenkins_pod_name> 0:8080
