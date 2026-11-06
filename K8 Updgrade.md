


<img width="826" height="157" alt="image" src="https://github.com/user-attachments/assets/4ee309e9-3fd7-498f-91f9-60e5a9306a03" />



#kubectl cordon aks-nodepool1-12345678-vmss000000

#kubectl get nodes

<img width="473" height="59" alt="image" src="https://github.com/user-attachments/assets/09b766ca-1f20-4eeb-b452-7066e0078784" />


Observe: Existing pods are still running. Cordon does not terminate existing pods.

Practise Drain:- 
kubectl drain aks-agentpool-35751002-vmss000000 \
  --ignore-daemonsets \
  --timeout=10m
