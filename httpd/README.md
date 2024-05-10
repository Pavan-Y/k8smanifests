kubectl get services httpd-service

find the Nodeport associated with the service(you can fix in either in service manifest 
or Kubernetes will pick a random one which you can check by above command).

We can access the httpd app on that port on all nodes of the Kubernetes cluster
