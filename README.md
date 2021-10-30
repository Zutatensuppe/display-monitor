# monitor-display-events

Monitors randr events and whenever such event occurs checks status 
of all displays. It will turn off active devices that are disconnected 
and turn on inactive devices that are connected.

At the moment, this probably only works with one external display, as it 
will always be put above the internal monitor.

## Usage

```
./monitor-display-events
```

## Requirements

- `bash`
- `xev`
- `xrandr`
- `awk/gawk`

## Resources

- https://unix.stackexchange.com/questions/13746/how-can-i-detect-when-a-monitor-is-plugged-in-or-unplugged
