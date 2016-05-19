# Docker

Role to install Docker and Docker Compose on an Ubuntu box

## Requirements

After downloading the role use the url on `atom/files/atom.deb.download` to download the installer and make sure its name matches the variable `ATOM_BUNDLE`.

##Role Variables

 * `DCKR_COMPOSE_VERSION` - the `docker-compose` version, defaults to `1.7.1`.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: docker, DCKR_COMPOSE_VERSION: 1.7.0 }

## License

MIT

## Author Information

Marco Shimomoto
