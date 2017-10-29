# gitlab-runner-ansible

## Preparation
1. copy file
  ```sh
  cp extra-vars.yml.sample extra-vars.yml
  ```
1. Edit extra-vars.yml
1. Install vagrant
  ```
  brew tap caskroom/cask
  brew cask install virtualbox vagrant
  ```

## How to use with vagrant
1. start vagrant
  ```
  vagrant up
  ```

1. run ansible-playbook
  ```
  ansible-playbook -i vagrant.py site.yml -e '@extra-vars.yml'
  ```



# references url
* [gitlab-runner register](https://gitlab.com/gitlab-org/gitlab-runner/blob/master/docs/commands/README.md#gitlab-runner-register)
* [The Haskel Tool Stack](https://docs.haskellstack.org/en/stable/README/)
* [Install docker-compose](https://docs.docker.com/compose/install/)
* [Install pip](https://docs.docker.com/compose/install/)
