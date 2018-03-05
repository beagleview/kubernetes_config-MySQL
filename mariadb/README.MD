# Create Secrte file for store password
kubectl create secret generic mariadb-pass --from-literal=password=YOUR_PASSWORD

# Run command for create MariaDB
kubectl create -f mariadb.yaml