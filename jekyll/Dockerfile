FROM gitpod/workspace-full

USER root

# Install Ruby
RUN apt-get update \
 && apt-get install -y ruby-full \
 && apt-get clean && rm -rf /var/cache/apt/* /var/lib/apt/lists/* /tmp/* \

USER gitpod

# install jekyll bundle
RUN gem install bundler jekyll
