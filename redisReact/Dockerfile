FROM mono:4.0.1
MAINTAINER james.leech@tattsgroup.com

ADD https://github.com/ServiceStackApps/RedisReact/raw/master/dist/RedisReact-console.exe /RedisReact/RedisReact-console.exe

EXPOSE 2337

ENTRYPOINT ["mono", "/RedisReact/RedisReact-console.exe"]

