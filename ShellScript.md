# Shell Script

## PID exists?

```
if pgrep -F $PIDFILE; then
  echo "Already running: $PIDFILE"
fi
```
