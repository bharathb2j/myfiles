import grove_rgb_lcd
# 4xLED plugged into pin 5
display = 5
grovepi.pinMode(display, &quot;OUTPUT&quot;)
grovepi.fourDigit_init(display)
grovepi.fourDigit_brightness(display, 8)
grovepi.fourDigit_number(display, 1234, False)
