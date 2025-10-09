    gpio18: Dir
    gpio19: Pulse

    gpio21: Dir
    gpio22 Pulse
    
    gpio16: Dir
    gpio17 Pulse
    
    gpio13: Dir
    gpio14 Pulse

# Tham khao
    [stepper_x]
    step_pin: gpio19
    dir_pin: gpio18
    #enable_pin: !gpio2
    full_steps_per_rotation: 200
    microsteps: 40
    rotation_distance: 40
    #endstop_pin: ^!EBBCan:PB6
    position_endstop: 646 #640
    position_min: -25
    position_max: 646 #640
    step_pulse_duration: 0.000020
    
    homing_speed: 30
    homing_retract_dist: 3.0
    homing_retract_speed:30
    second_homing_speed:7
    homing_positive_dir: true
