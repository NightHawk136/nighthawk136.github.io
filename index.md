## Hello, my name is Zach

I am a somewhat experienced web developer. While I mainly use HTML or Python I am always open to learning new languages.
This webpage will mainly be used for project updates and well games. Feel free to explore and if you have any questions or comments go to the help page! Have fun. Git coding!

### Getting Started With GUIS

A snippet of my curent project code will go in the code block below.

```python
from guizero import App
from guizero import App, Text
from guizero import App, TextBox
from guizero import App, PushButton
from guizero import App, Slider

def say_my_name():
    welcome_message.set( my_name.get() )

def change_text_size(slider_value):
    welcome_message.font_size(slider_value)

app = App(title="Hello world")
welcome_message = Text(app, text="Welcome to my app")
my_name = TextBox(app)
update_text = PushButton(app, command=say_my_name, text="Display my name")
text_size = Slider(app, command=change_text_size, start=10, end=80)



app.display()
```

For more details on this project see [RaspberryPi Tutorials](https://www.raspberrypi.org/learning/getting-started-with-guis/).

### Join GalaxyRocket101

If you would like to join my GitHub team please send me an email at nighthawk136@outlook.com. Be sure you include your name, email, and a brief description about yourself, and I will get back to you as soon as possible.

### Chat and General Info

Feel free to use my chat to give tips, ideas, comments, question, and if you just want to say hello. [Click Here](https://join.slack.com/galaxyrocket101nh/shared_invite/MTc3MTA2ODQxNzQ1LTE0OTM3NTIwMTUtYjE1ZjgyYTg0ZA) for chat.

Thanks again! Zach, NightHawk136
