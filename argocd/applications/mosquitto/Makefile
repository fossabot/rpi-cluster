install-chart:
	helm repo add k8s-at-home https://k8s-at-home.com/charts/

render:
	helm template mosquitto k8s-at-home/mosquitto -f helm/values.yaml > resources.yaml
