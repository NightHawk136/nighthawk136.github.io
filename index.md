## Hello, my name is Zach

I am a somewhat experienced web developer. While I mainly use HTML or Python I am always open to learning new languages.
This webpage will mainly be used for project updates and well games. Feel free to explore and if you have any questions or comments go to the [help](https://nighthawk136.github.io/help/) page! Have fun. Git coding!

### Getting Started With GUIS

A snippet of my curent project code will go in the code block below.

```python
from guizero import App
from guizero import App, Combo
from guizero import App, Text
from guizero import App, CheckBox
from guizero import App, ButtonGroup
from guizero import App, PushButton
from guizero import App, info

def do_booking():
    info("Booking", "Thank you for booking")
    print( film_choice.get() )
    print( vip_seat.get_value() )
    print( row_choice.get() )

app = App(title="My second GUI app", width=300, height=200, layout="grid")

film_choice = Combo(app, options=["none", "Star Wars", "Indiana Jones", "Batman"], grid=[0,1], align="left")

film_description = Text(app, text="Which film?", grid=[0,0], align="left")

vip_title = Text(app, text="Seat type", grid=[1,0])

vip_seat = CheckBox(app, text="VIP seat?", grid=[1,1], align="left")

row_name = Text(app, text="Seat location", grid=[2,0])

row_choice = ButtonGroup(app, options=[ ["Front", "F"], ["Middle", "M"],["Back", "B"] ],
selected="M", horizontal=True, grid=[2,1], align="left")

book_seats = PushButton(app, command=do_booking, text="Book seat", grid=[3,1], align="left")

app.display()
```

For more details on this project see [RaspberryPi Tutorials](https://www.raspberrypi.org/learning/getting-started-with-guis/).

### Join GalaxyRocket101

If you would like to join my GitHub team please send me an email at nighthawk136@outlook.com. Be sure you include your name, email, and a brief description about yourself, and I will get back to you as soon as possible.

### Chat and General Info

Feel free to use my chat to give tips, ideas, comments, question, and if you just want to say hello. [Click Here](https://join.slack.com/galaxyrocket101nh/shared_invite/MTc3MTA2ODQxNzQ1LTE0OTM3NTIwMTUtYjE1ZjgyYTg0ZA) for chat.

Thanks again! Zach, NightHawk136
