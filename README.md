Physical Computing build for a Raspberry Pi Pico 2w MQTT Robot.
Code assumes your pico is registered for the BostonCollege (not eduroam).
Web-based control dashboard is at:
http://makerspaceserv.bc.edu:3000/
Make sure you modify your code so that the value below uses your BC username:
feeds = "username"
And when using the web dashboard, enter the Topic: field like this:
/username/move_feed
where, of course username above is YOUR specific BC username.
Also make sure you're using the settings.toml file settings included in this repo.

Parts:
- Raspberry Pi Pico 2W - https://www.adafruit.com/product/6315
- Two continuous rotation servos - https://www.adafruit.com/product/2442
- Breadboard (we use the Monk Makes board because it shows the Pico wiring on the board) - https://www.adafruit.com/product/5422
- Robot Chassis - https://www.adafruit.com/product/2943
- Supporting Swivel Caster Wheel - 1.3" Diameter - https://www.adafruit.com/product/2942
- Pin-Pin jumper wires - https://www.adafruit.com/product/1957
- A mobile phone battery - just make sure it doesn't have an "auto-shutoff" or auto "sleep-mode" as this may turn off your robot when it's just idling.
- Double-sided velcro tape

<img width="1301" height="732" alt="robo_wiring" src="https://github.com/user-attachments/assets/32eb8287-80cc-4271-a752-31b3464b148e" />
