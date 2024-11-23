# Volumes in Kubernetes

We can use volumes in Kubernetes for the data persistent.We
can have different types of volumes in Kubernetes.Some of the
most commonly used volumes are:

- emptyDir
- hostPath
- nfs
- csi

## emptyDir

They are temporary volumes that are created when a Pod
is assigned to a Node and are deleted when the Pod is removed from the Node.

Use Cases:

- suitable for storing temporary data
- logs and caches