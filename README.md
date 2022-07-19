# agriaf-mongodb


helm repo add mongodb https://mongodb.github.io/helm-charts

helm install community-operator mongodb/community-operator

kubectl apply -f mongodbcommunity_cr.yaml
