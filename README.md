# https://getElementsByName.github.io

### development
- https://jekyllrb.com/docs/
- prerequisites
  - https://jekyllrb.com/docs/installation/
  - jekyll, bundler
```
gem install jekyll bundler
```

- install gem dependencies
```
bundle install
```

- start local server to build
```
bundle exec jekyll serve
```


### ruby
- rbenv
```
git clone https://github.com/rbenv/rbenv.git ~/.rbenv

echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc

source ~/.bashrc
```


```
rbenv install -l
rbenv install 3.1.2

rbenv global 3.1.2
```