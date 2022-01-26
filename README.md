# PaaS-Datastore-APIAssignment-main
 Task PaaS-Datastore-APIAssignment for SSE

 ##Installation

gcloud compute instances create --machine-type f1-micro  \
          --tags http-server,https-server  inst1

curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs git

npm install express
npm install body-parser
npm install @google-cloud/datastore
git clone https://github.com/Samourai-cat/PaaS-Datastore-APIAssignment-main.git
npm start