# nsx-t-policy-api
Contain samples on how to use NSX-T Policy API

Step 1:
git clone https://github.com/vincenthanjs/nsx-t-policy-api.git

Step 2:
cd nsx-t-policy-api

Step 3:
curl -i -k -X PATCH -u admin:VMware1!VMware1! -H "Content-Type: application/json" -H "Accept: application/json" -d @Infra-Create-Lab1-v1.0 https://172.16.14.15/policy/api/v1/infra
