# ComfyBlog [![Build Status](https://secure.travis-ci.org/comfy/comfy-blog.png)](http://travis-ci.org/comfy/comfy-blog) [![Dependency Status](https://gemnasium.com/comfy/comfy-blog.png)](https://gemnasium.com/comfy/comfy-blog)

ComfyBlog is an simple blog management engine for Rails 4 apps. It also integrates with [ComfortableMexicanSofa](https://github.com/comfy/comfortable-mexican-sofa) CMS Engine

## Installation

Add gem definition to your Gemfile:

```ruby
gem 'comfy_blog', '~> 1.0.0'
```

```ruby
ComfyBlog::Routing.admin   :path => '/admin'
ComfyBlog::Routing.content :path => '/'
```