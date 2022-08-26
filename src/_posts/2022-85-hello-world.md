---
layout: post
title:  "Hello World Component Example"
cloudinary_id: 1659372357/sample.jpg
date:   2022-08-25 17:32:09 -0400
categories: updates
---

src/_components/hello_world.js.rb

```ruby
class HelloWorld < HTMLElement
  def connected_callback()
    self.inner_html = "<p><strong>Hello World!</strong></p>"
  end
end

# Try adding `<hello-world></hello-world>` somewhere on your site to see this
# example web component in action!
custom_elements.define "hello-world", HelloWorld

```

Check out the [Bridgetown docs](https://bridgetownrb.com/docs/) for more info on how to get the most out of Bridgetown. File all bugs/feature requests at [Bridgetown’s GitHub repo](https://github.com/bridgetownrb/bridgetown). If you have questions, you can ask them on [Bridgetown Discussions on GitHub](https://github.com/bridgetownrb/bridgetown/discussions).

<hello-world></hello-world>