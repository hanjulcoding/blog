# Hanjulcoding Blog

[https://blog.hanjulcoding.com](https://blog.hanjulcoding.com)

### YouTube

[https://www.youtube.com/channel/UCS6loxXbMlAL8VwSVM4UIKQ](https://www.youtube.com/channel/UCS6loxXbMlAL8VwSVM4UIKQ)

---

### Github
[https://github.com/hanjulcoding/blog](https://github.com/hanjulcoding/blog)

---

## How to Use

로컬 서버 실행 (http://localhost:4000)
```
gem install bundler jekyll
bundle install
bundle exec jekyll s
```

배포 전 테스트
```
bundle exec jekyll build
bundle exec htmlproofer _site \-\-disable-external=true \-\-ignore-urls "/^http:\/\/127.0.0.1/,/^http:\/\/0.0.0.0/,/^http:\/\/localhost/"
```
  
## License

This work is published under [MIT][mit] License.

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy/
[mit]: https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE
