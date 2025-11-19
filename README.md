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
- Raspberry Pi Pico 2W
- Two continuous rotation servos
- Breadboard (we use the Monk Makes board because it shows the Pico wiring on the board)
- Robot Chassis
- Pin-Pin jumper wires
- A mobile phone battery

<img width="1301" height="732" alt="robo_wiring" src="https://github.com/user-attachments/assets/32eb8287-80cc-4271-a752-31b3464b148e" />
