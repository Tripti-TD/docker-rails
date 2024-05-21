# README


![his1](https://github.com/Tripti-TD/docker-rails/assets/128075759/9fa51d3a-2d4d-429a-910b-cd98b6b25f00)

build image with Dockerfile
< FROM ruby:2.5.9
 RUN apt-get update && apt-get install -y nodejs
 WORKDIR /app
 COPY Gemfile* ./
 RUN bundle install
 COPY . .
 EXPOSE 3000
 CMD ["rails", "server", "-b", "0.0.0.0"] >
 
![bulding](https://github.com/Tripti-TD/docker-rails/assets/128075759/b45581b8-6995-4e33-ace4-c563de5cc4d5)

docker-compose.yml file

![processing](https://github.com/Tripti-TD/docker-rails/assets/128075759/8e9869af-7c62-417b-af19-832988cae47f)

all containers and images

![containers](https://github.com/Tripti-TD/docker-rails/assets/128075759/964cda6c-1039-4176-8b52-3d22e1254b55)


![webpage](https://github.com/Tripti-TD/docker-rails/assets/128075759/2a29275a-cbf8-4a22-a474-a1305018d953)

pushing it to repo

![push to repo](https://github.com/Tripti-TD/docker-rails/assets/128075759/7c4b5f48-bb3a-4f49-b336-fcad1c1dca15)





