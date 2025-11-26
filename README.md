```
npm create wagmi@latest 
```

project name: wawgmi-dapp-demo-01

select React 

select Next 2

cd wawgmi-dapp-demo-01

```
npm install
npm run dev
```

```
ssh-keygen -t rsa -b 4096 -C "YOUR-EMAIL.com"
```
```
cat ~/.ssh/id_rsa.pub
```

paste into git -> settings -> SSH and GPG keys -> New SSH key

```
git init
git add .
git commit -m "first commit."
git branch -M main
git remote add origin YOUR_REMOTE_ORIGIN
git push -u origin main
```

running Docker containers

```
docker run --rm -d -p 3001:3000 IMAGE_ID
```

push to Docker Hub

Create a personal access token and use it to log in to Docker

```
docker tag IMAGE_NAME DOCKER_HUB_REPO_NAME

