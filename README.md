# matrix_wall_follower
Wall (corridor) Follower

1. Sub the /scan_f_raw
2. left = scan_f_raw(0 ~ 30) degrees
3. right = scan_f_raw(340.8 ~ 358.5) degrees
4. clip left and right, Max=3.0, Min=0.1
5. merge the clipped left and right and assign it as the "stop_zone_clipped"
6. calculate average value of the "stop_zone_clipped" as the "stop_zone_avr"
7. convert the "stop_zone_avr" from 0.01~2.5 to 0.0~1.0

to be continue
