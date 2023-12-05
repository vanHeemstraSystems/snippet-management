# IT-Tools

Based on "IT-Tools" at https://it-tools.tech

Example of a Docker compose file for it-tools.tech:

```
...
it-tools:
  image: corentinth/it-tools
  container_name: IT-Tools
  networks:
    pihole:
  ports:
    - 36292:80
  restart: always
...
```
