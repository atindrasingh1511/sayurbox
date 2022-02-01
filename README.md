# sayurbox

DEVOPS Assigment

1. Create a helm chart for a frontend web-server ( vaibhavmehta/pwa-weather-app or
you may choose anyone you want ), bonus points for writing your own app.
2. Deployment specs:
a. All configuration either in environment or ConfigMap
b. CPU request/limit : 50m/150m
c. Memory request/limit : 80MB/128MB
d. Node Affinity:
- app-deployment = true
- db-deployment = false
- monitoring-deployment = fals
e. App update strategy: Rolling update
f. Specify HPA/HA and PDB for the pod
- HA/HPA : min/max 5/10
- PDB: 2

3. Enable and specify health-check.
4. All configuration to be used from 'values.yml' file.
