# ansible-pull-docker<br />
# testing ansible pull inside a debian docker<br />
apt-get update<br />
apt get -install -y ansible git<br />
ansible-pull -U https://github.com/Dispelk9/ansible-pull-docker.git test_pull.yml

to pull a new Ubuntu KVM using ansible-pull
ansible-pull -U https://github.com/Dispelk9/ansible-pull-docker.git kvm_initial.yml
