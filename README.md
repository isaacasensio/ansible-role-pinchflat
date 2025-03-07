pinchflat
==========

Installs pinchflat as a docker container service.


Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):


```
pinchflat_image: ghcr.io/kieraneglin/pinchflat:latest
```
The version of the pinchflat image to run as a container.

```
pinchflat_host_config_path: /etc/pinchflat
```
Host path where the pinchflat configuration will be stored.

```
pinchflat_host_data_path: /var/lib/pinchflat
```
Host path where the pinchflat data will be stored.

```
pinchflat_container_user: pinchflat
```
user who will run the container

```
pinchflat_host_port: 8945
```
host port exposed

```
pinchflat_timezone: Europe/Berlin
```
Timezone



Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - iasensio.pinchflat

License
-------

MIT

