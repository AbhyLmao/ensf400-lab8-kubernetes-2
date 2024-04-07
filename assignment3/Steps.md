# °˖✧˚ʚ♡ɞ˚✧˖°
ENSF 400 Assignment 1\
Abhyudai Singh - 30157580 

## - Pre-requsites
* Make sure minikube is running, if minikube is not running use the command -

```bash
minikube start
```
* Make Sure to enable the addon ingress - 
```bash
minikube addons enable ingress
```



## - Apply the configurations 
* To apply changes to all the files at once, use -
```bash
kubectl apply -f .
```

* To apply changes to one file at a time, use -
```bash
kubectl apply -f <file-name>
```

## - Test your configuration

* To get the IP address, run the command -
```bash
minikube ip
```

* Use the output from the command above, and run - 
```bash
curl http:// <ip> /

```

* To do both in the same step - 
```bash
curl http://$(minikube ip)/
```

## - Check your deployments/Troubleshoot


\
\
\
˚₊‧꒰ა ☆ ໒꒱ ‧₊˚