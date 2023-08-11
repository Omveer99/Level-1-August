# Copy the IDE and open in incognito
# Open terminal and Paste this command

```bash
git clone https://github.com/rosera/pet-theory.git
cd ~/pet-theory/lab02
npm i && npm audit fix --force
gcloud config set compute/region us-central1
gcloud app create --region=us-central
gcloud firestore databases create --region=us-central
```
# Now do the rest tasks manually with the help of video
