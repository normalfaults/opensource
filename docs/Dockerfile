FROM docs/base:oss
MAINTAINER Mary Anthony <mary@docker.com> (@moxiegirl)

ENV PROJECT=opensource

# To get the git info for this repo
COPY . /src
RUN rm -rf /docs/content/$PROJECT/
COPY . /docs/content/$PROJECT/
