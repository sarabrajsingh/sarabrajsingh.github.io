FROM ruby:2.7

WORKDIR /home/app

COPY Gemfile* ./

RUN bundle install

COPY . .

EXPOSE 4000

CMD [ "bundle", "exec", "jekyll", "serve" ]