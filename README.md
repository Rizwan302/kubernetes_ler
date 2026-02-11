## 🗓 Daily Learning Tracker

> ### ✅ Day 1 – Kubernetes Namespace  
> 📅 **Date:** ___________  
>  
> │ • Learned what a Kubernetes Namespace is  
> │ • Understood use-cases (isolation, environments)  
> │ • Created a custom namespace using YAML  
> │ • Verified namespace creation  
> │  
> │ **Commands Used:**  
> │ ```bash
> │ kubectl get namespaces
> │ kubectl apply -f namespace.yml
> │ kubectl describe namespace dev
> │ kubectl delete namespace dev
> │ ```
> │  
> │ **File Created:**  
> │ • `namespace.yml`
> 
>  ### ✅ Day 2 – Namespace Practice  
> │ • Deployed resources in a specific namespace  
> │ • Used namespace flag in kubectl commands  ← **New point added**  
> │ • Switched default namespace context  
> │ • Deleted namespace after testing  
> │  
> │ **Commands:**  
> │ kubectl get pods -n dev  
> │ kubectl config set-context --current --namespace=dev  
> │ kubectl delete namespace dev
