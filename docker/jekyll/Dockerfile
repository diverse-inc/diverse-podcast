FROM ruby:2.7.1

WORKDIR /app

COPY \
  Gemfile \
  Gemfile.lock \
  /app/
RUN bundle install --jobs=4 --path=/bundle
