# Change Log

## 1.4.2

### [1.4.2b1](https://github.com/dbaldwin/DronePan/releases/tag/1.4.2b1)

#### Updates

* Update to DJI SDK 3.1
* Faster - we now react to the device saying "finished" instead of waiting long enough that we think it worked - so panoramas should go faster
* More stable - since we actually check for move completion and camera shot saved to disk - we should finally be **quit the missing shot bug** - in fact it'll retry up to 5 times for each move and photo
* Osmo support
* Phantom 4 support
* Delay on start (Osmo) - your "get out of shot" time
* Choose number of photos in row
* Choose extra sky row (point the gimbal up to 30˚) - aircraft only (Osmo will always do it's full gimbal pitch)

#### Known issues

* Even if you enable sky row for P3 in DJI Go - it doesn't allow it via the SDK - so it will skip the sky row (and tell you it can't make that move)