vault server -dev

export VAULT_ADDR='http://127.0.0.1:8200'

vault kv put secret/product-microservice @product-microservice.json 
vault kv put secret/booking-microservice @booking-microservice.json
