# Organização do conteúdo de Ciência de Dados do canal Programação Dinâmica


# Running locally
- [install docker](https://docs.docker.com/engine/install/) 
- Run ```docker run -i -t --rm -u 1000:1000 -p 4000:4000 -v `pwd`:/opt/app -v `pwd`/.bundler/:/opt/bundler -e BUNDLE_PATH=~/opt/bundler -w /opt/app ruby:2.7 bash -c "bundle install && bundle exec jekyll serve --watch -H 0.0.0.0"```

---
Course-in-a-Box was built by [Peer 2 Peer University](https://www.p2pu.org) using the [P2PU Jekyll course template](https://github.com/p2pu/jekyll-course-template) and shared under an MIT License.

Course content ("Modules") are shared under a [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/).
