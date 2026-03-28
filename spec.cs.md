# Funny Geese Demo

The app animates geese (🪿) bouncing around the screen, tumbling.

## UX

A click on a free space creates a new medium-sized goose flying in a random direction.

A click on a goose makes it bigger. When a goose gets too big it disappears with an animated pop.

## UI

### Speed Slider

The bottom-right corner has a speed slider:
- in the middle by default
- moving the slider to the left slows the geese down
- moving to the right speeds them up

### Stats

In the top-right corner, a leaderboard of all players is displayed. For each player, it shows:
- name
- number of geese created
- number of geese popped 🎉

Every player gets a random name from a list of names built by combining a cute adjective with an animal name, e.g. "Huggable Alpaca" and an emoji avatar, e.g. 🦙.

Stats are updated in real time.

## Technology

- HTML + JS
- Django
- Use Tailwind CSS for styling
