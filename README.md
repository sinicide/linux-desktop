# README

Automated deployment of my Desktop Environment (Linux of course)

## TODO

- [ ] Everything
- [ ] Laptop Specific Configs vs Desktop
- [ ] NUT UPS Configuration
- [ ] Gotify Notification Service
- [ ] Deploy dotfiles
- [ ] Fix flathub install due to remote hub

### Apps List

- braytech and dim
- spectacle (screenshot)

## Install Requirements

```
ansible-galaxy install -r requirements.yaml
```

## Run Play

```
ansible-playbook -K -i localhost.yaml setup.yaml
```

### For Laptop

```
ansible-playbook -K -i localhost.yaml setup.yaml --extra-vars "laptop=true"
```

