# Loop Time

Dynamic, responsive countdown rings with a 3D gyroscope-like finish.

![Gyroscope](https://images.unsplash.com/photo-1635070041078-e363dbe005cb?w=600&q=80)

## Usage

Try it at `liamsimpkin.com/◎`

**Query Parameters** (ISO 8601 format):
- `?start=` — Countdown start time
- `?end=` — Countdown end time

**Example**:
```
liamsimpkin.com/◎?start=2025-11-24T21:22:15+13:00&end=2025-12-03T06:30:00+13:00
```

[View a past timer example →](https://liamsimpkin.com/◎?start=2025-01-01T00:00:00+13:00&end=2025-01-01T12:00:00+13:00)

**How it works**: Three synchronized rings track overall progress (outer), hourly cycles (middle), and minute cycles (inner). When the countdown completes, the rings transform into a rotating 3D gyroscope.

**Configuration**: Adjust rotation speed by modifying `ROTATION_SPEED_FACTOR` in [index.html:162](index.html#L162) — `1.0` = base speed, `2.0` = double speed, `0.5` = half speed.
