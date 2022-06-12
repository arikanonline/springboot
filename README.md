######################################################
# Architecture
# Microsoft Azure include 2 VM
# 1 Kubernetes Master + 1 Kubernetes Worker Node
# 1 Hello-world app (1 Deployment + 1 Service + 2 Pod)
# 1 Jenkins app (1 Statefulset + 1 Service + 1 Pod)
######################################################
# Hello-World App Road Map;
# New Request URL --> marikan.tk
# marikan.tk --> Azure DNS --> Kubernetes Worker Node
# marikan.tk --> Ingress --> hello-world service
######################################################
# Hello-World CI/CD Road Map;
# first pipeline manuel build (Optional)
# second pipeline when commit github repository automatically build (Optional)
######################################################

Written by Mehmet ARIKAN
