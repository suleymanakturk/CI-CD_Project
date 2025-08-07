# CI-CD_Project

Merhaba,

Bu projede aşağıdaki adımları içeren bir CI/CD örneği kurgulayacağız. Aşağıdaki toollardan docker ve kubernetes benim ortamımda kurulu bulunmaktadır. Diğer tolları ise proje aşamasında kurup , konfigure edeceğiz.


1- Kubernetes Üzerine Jenkins Kurulumu
2- Jenkins Konfigurasyonu ve Github ile Webhook Konfigurasyonu
3- Ngrok ile webhook servisini dışarı açma
3- Projeyi Githuba Push Et
4- Jenkins Pipeline Yazılacak. Pipeline üzerinde aşağıdaki adımlar gerçekleştirilecektir.
	a. Docker ile build et
	b. Docker Huba push et
	c. Kubernetes üzerinde çalıştır
	d. Servisi nginx ingress ile dışarıya aç
	e. Grafana ile monitor et
5- ArgoCD ile Gitops


Gerekli Toollar

Docker 
Kubernetes
Jenkins
Kustomize
Github 
ArgoCD
Ngrok
