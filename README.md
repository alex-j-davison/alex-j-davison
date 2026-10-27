# Pacman Helm Chart Repository 

## Usage

```bash
helm repo add Pacman https://alex-j-davison.github.io/alex-j-davison/
helm repo update

kubectl create namespace pacman

helm install pacman -n pacman pacman/pacman