# jenkins

	gcloud compute disks create jenkins --size 50GB
	kubectl apply -f jenkins.dpl.yml
	kubectl apply -f jenkins.svc.yml

	kubectl -n kube-system <jenkins_pod_name> 0:8080
