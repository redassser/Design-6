### [<- Return](../../)

# Lab 6

I actually have many years in Node.js development experience!
Check out [my website](https://rpie.dev) made with Next.js
or this other cooler site about [assembly](https://redassser.github.io/ASM/)

ok no more onto the lab

### Node.js 

```bash
ryan@rpi:~/iot/lesson6 $ node hello-world.js
Server running at http://127.0.0.1:3000/
```

[image of hello, world]

```bash
ryan@rpi:~/iot/lesson6 $ node hello.js
Server running at http://127.0.0.1:8080/
response end call done
request end event fired
```

[image of hello]

```bash
ryan@rpi:~/iot/lesson6 $ node http.js
0

1
2
```

[image of refreshed]

### Pystache

```bash
ryan@rpi:~/iot/lesson6 $ cat say_hello.mustache
Hello, {{to}}!
ryan@rpi:~/iot/lesson6 $ cat say_hello.py
# https://github.com/defunkt/pystache
import pystache
print(pystache.render('Hi {{person}}!', {'person': 'Alexa'}))

# Create dedicated view classes to hold view logic
class SayHello(object):
    def to(self):
        return "World"
hello = SayHello()

# Use template in say_hello.mustache
renderer = pystache.Renderer()
print(renderer.render(hello))

# Pre-parse a template
parsed = pystache.parse('Hey {{#who}}{{.}}!{{/who}}')
print(parsed)
print(renderer.render(parsed, {'who': 'Google'}))
print(renderer.render(parsed, {'who': 'Siri'}))
ryan@rpi:~/iot/lesson6 $ python3 say_hello.py
Hi Alexa!
Hello, World!

['Hey ', _SectionNode(key='who', index_begin=12, index_end=18, parsed=[_EscapeNode(key='.'), '!'])]
Hey Google!
Hey Siri!
```
