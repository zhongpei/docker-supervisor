# docker-supervisor

## Usage

###first

write your supervisord.conf

###run it
```sh
docker run -d -v $(PWD)/supervisord.conf:/etc/supervisord.conf   zhongpei/supervisor
```
