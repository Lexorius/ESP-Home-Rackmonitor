Hi, 
this is a small sensor build for the raspberry pi pico w . It is ment to go into some 19" racks to messure the temperatur and all relevant things. 


31.11.2024: 

  the first batch of the PCB was delivered today - the first test where done. At The Moment the wholes for the display are a little bit to small, but you can soder a display to it. i've killed two bme680 in testing (i guess it was the sensors from the bradboard)

  The sensor could now :
  
      - Messure 
          - Temperature
          - Humidity
          - Pressure
          - Gas Resistance (what ever that means)
          - two binary sensor / door sensors
          - adc sensor that senses 0-3.3V. aka watersensor
      - the display shows:
          - wifi strength
          - Rack number / or text
          - Clock from NTP Server
          - Tempreture and humidity

      - Missing Features / Failures: 
          - external sensor
          - Made the Raspberry Pi Pico W on the wrong side. 
          - Hole for display connector to small

--------------------------------------------------------------------------------------------------------------------------------          

Features wishlist: 
  - ~~the sensor should integrate into home assistant~~
  - ~~easy to replicate~~
  - ~~Temperatur / humidity~~
  - ~~Door sensor~~
  - ~~Water leakage sensor~~
  - maybe external temperature sensor
  - ~~Display optional~~


