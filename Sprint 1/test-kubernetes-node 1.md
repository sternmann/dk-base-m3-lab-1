# Probar Kubernetes en nodo 1

Objetivos
- Crear namespace y pods monitoreando su estado con la modalidad watch

Tareas
Crear namespace, monitorear cambios a etiquetas en modalidad watch
Monitorear cambios a eventos de pods, crear pod de corta duración


$ kubectl get namespace sternmann -o yaml
apiVersion: v1
kind: Namespace
metadata:
  creationTimestamp: "2023-08-11T02:32:31Z"
  labels:
    kubernetes.io/metadata.name: sternmann
  name: sternmann
  resourceVersion: "3051"
  uid: 2394ed83-2226-4767-a73b-792570dbcec3
spec:
  finalizers:
  - kubernetes
status:
  phase: Active
