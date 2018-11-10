# Ingress Controller with Automatic DNS entry.

```
            Create IAM policy - put-node-policy.sh
            Start your Ingress  - kubectl create -f nginx-ingress-server.yaml
            Create Load Balancer for Ingress - kubectl apply -f service-l4.yaml
            Create DNS and Ingress rules - kubectl create -f external-dns.yaml -f ingress.yaml
                
 ```

