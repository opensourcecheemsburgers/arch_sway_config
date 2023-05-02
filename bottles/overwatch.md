# Settings
- dxvk-async
- caffe-7.20
- use discrete gpu 
- feral gamemode

# Environment Variables for Overwatch

| Key                                   | Value                         |
| -----------------------------------   | ----------------------------- |
| `__GL_SHADER_DISK_CACHE_PATH`         | /home/$USER/bottles/Overwatch |
| `DXVK_STATE_CACHE_PATH`               | /home/$USER/bottles/Overwatch |
| `STAGING_SHARED_MEMORY`               | 1                             |
| `__GL_SHADER_DISK_CACHE`              | 1                             |
| `__GL_SHADER_DISK_CACHE_SKIP_CLEANUP` | 1                             |

## Warning
- Do **not** enable `LatencyFlex`, it trips the anticheat.
- Do **not** enable `Fullscreen Mouse Capture`, your mouse will not work in game.

## Notes
- I use CoreCtrl to change my gpu's fan speed and clocks.
- Enabling `AMD FSR` in game seems to give a significant performance increase and reduce stuttering.
- I recommend using the dxvk-cache file from https://github.com/Elagoht/overwatch2-dxvkcache.
Place the file in the root of your Overwatch bottle e.g `/home/$USER/bottles/Overwatch`
