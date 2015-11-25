# docker-supervisor

## Usage

###supervisord.conf

modify your `supervisord.conf`

###run it
```sh
docker run -d -v $(PWD)/supervisord.conf:/etc/supervisord.conf   zhongpei/supervisor
```
