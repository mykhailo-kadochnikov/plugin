# Installing kubectl plugins
A plugin is a standalone executable file, whose name begins with kubectl-. To install a plugin, move its executable file to anywhere on your PATH.

# Uses
For using plugin you need use this command kubectl kubeplugin <resourcetype> <namespace>

# Sample
kubectl kubelugin pods argocd
# Answer
argocd-application-controller-0, 11m, 164Mi           
argocd-applicationset-controller-585dc88ddd-rfz9m, 3m, 23Mi            
argocd-dex-server-5c6fbfb79d-l5fh6, 6m, 41Mi            
argocd-notifications-controller-5d64b957b-89csg, 9m, 64Mi            
argocd-redis-69f8795dbd-zb22p, 4m, 9Mi             
argocd-repo-server-648995ccf4-bnvl7, 1m, 85Mi            
argocd-server-689dc7ff86-5zqmg, 3m, 45Mi
