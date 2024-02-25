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

![IMG_20240225_003809937](https://github.com/redassser/Design-6/assets/40395425/00ff6327-8b20-495b-980b-619b880181f3)

```bash
ryan@rpi:~/iot/lesson6 $ node hello.js
Server running at http://127.0.0.1:8080/
response end call done
request end event fired
```

![IMG_20240225_004053680](https://github.com/redassser/Design-6/assets/40395425/24ebf508-3cc6-4d0c-b940-e363059927d2)

```bash
ryan@rpi:~/iot/lesson6 $ node http.js
0

1
2
```

![IMG_20240225_004322461](https://github.com/redassser/Design-6/assets/40395425/e9165acd-d39a-41c9-9e89-66785fc114f2)

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
