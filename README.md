# agic-demo
all the things used in application gateway implementation

Commands:

az vm create \
  --resource-group demoagirg \
  --name ubuntuDemoVM \
  --image Ubuntu2204 \
  --size Standard_B1s \
  --admin-username azureuser \
  --generate-ssh-keys \
  --custom-data cloud-init.txt


