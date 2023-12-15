
Kubernetes (kubeadm/kubectl/kubelet) installés

Tentative d'initialisation de cluster

Etapes pour lancer un cluster :

- kubeadm init (--config config-file.yaml) : sur le master node pour créer le cluster
- kubeadm join ... : sur chaque worker node pour les ajouter au cluster
