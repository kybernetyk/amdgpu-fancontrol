# amdgpu-fancontrol

fork for my system. also tried adding fan stop but as it turns out letting the fans stop and rev up is more annoying than having the fans constantly run at min_rpm. :clownworld:

/edit: yes, I know the original repo supports fanstop by setting pwm to 0. but my card is a special card and needs a rpm of 92 to start fans but can go as low as pwm 82 and keep fans running. so with 0 pwm the fans would stay stopped for too long resulting in a louder fan-start than neccessary. (you must know: I'm very smart) 
