### pygments.rb 
---
https://github.com/tmm1/pygments.rb

```ruby
require 'pygments'
Pygments.highlight(File.read(__FILE__), :laxer => 'ruby')
Pygments.highlight('code', :optons => {:encoding => 'utf-8'})
Pygments.highlight('code', :formatter => 'bbcode')
Pygments.highlight('code', :formatter => 'terminal')
Pygments.css
Pygments.css('.highlight')
Pygments.css(:style => "monokai")

Pygments.laxers
Pygment.formatters
Pygment.styles
Pygments.start("/path/to/pygments")


```


```
ruby bench.rb 50
ruby bench.rb 10


```

```
```
