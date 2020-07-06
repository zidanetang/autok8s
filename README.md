# autok8s
Used to automatically setup, maintain and recycle the k8s
ansible-playbook -i catalog/inventory/hosts k8s-master-single.yml -vvvv -e Role=k8s-master


阿里云registry.cn-hangzhou.aliyuncs.com/google_containers/kube-apiserver-amd64   v1.18.2
