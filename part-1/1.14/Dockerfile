FROM ruby:2.6.0

WORKDIR /usr/src/app

COPY Gemfile Gemfile.lock ./
RUN bundle install

COPY . .

RUN rails db:migrate

EXPOSE 3000

CMD ["rails", "s"]