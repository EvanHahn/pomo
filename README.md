pomo
====

a command-line Pomodoro.

```
$ pomo
welcome to pomo

work started
  25m left of work
  24m left of work
  ...

break started
  5m left of break
  ...

work started
  25m left of work
  ...
```

to configure, create `~/.pomoconfig`. here's a sample:

```
work_time 30
short_break_time 3
long_break_time 45
pomodori 4
event_command 'tput bel'
```

the only confusing one is `event_command`. this is run every time you enter a new time interval (start work or start a break). you could play a sound, have it stop your music, or something else.
