# Attendance, simplified.

## Mission

Automate the attendance taking process by allowing students to scan their student ID card upon entering a classroom, sending their name to a web application that shows the teacher a simple list of everyone who's scanned in.

## Current Blueprint

Most current diagram of what our solution will look like:

![Current project diagram](Capstone_Diagram.png)

## Shopping List

List of things we need to buy for the project:

| Item | Cost |
|-|-|
|[HiLetgo RFID Reader](https://www.amazon.com/HiLetgo-125Khz-EM4100-Reader-Swipe/dp/B01MZYYDUV/ref=asc_df_B01MZYYDUV/?tag=hyprod-20&linkCode=df0&hvadid=674654857821&hvpos=&hvnetw=g&hvrand=11910253218607601018&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9019656&hvtargid=pla-1640410588708&psc=1&mcid=a09c09b05a833b37b181317aefde13cc) | $10.49 |
|[Raspberry Pi Zero W (TBD)](https://www.amazon.com/Raspberry-Pi-Zero-Wireless-model/dp/B06XFZC3BX/ref=asc_df_B06XFZC3BX/?tag=hyprod-20&linkCode=df0&hvadid=312363697617&hvpos=&hvnetw=g&hvrand=12255993669550297530&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9019669&hvtargid=pla-405706373744&psc=1&mcid=7c324a0a86243324915c51bfb077f963&tag=&ref=&adgrpid=61916342293&hvpone=&hvptwo=&hvadid=312363697617&hvpos=&hvnetw=g&hvrand=12255993669550297530&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9019669&hvtargid=pla-405706373744&gclid=Cj0KCQiAqsitBhDlARIsAGMR1Rh3R2iQx6Wp9i3mGJZ7Fr_0tgGDG1drqlVJABb0oX2EUVb8bdxf-iMaAvdREALw_wcB)| $20.80 |
|Running total | **$31.29** |

See [`HardwareReqs.xlsx`](HardwareReqs.xlsx) for downloadable spreadsheet.

## To-do List

What's next on the docket?

- [ ] Get card reader ordered
- [ ] Experiment with card reader, determine it's output
- [ ] Research Raspberry Pi, determine what will work best for our needs
- [ ] Order Pi, configure networking and OS
- [ ] Connect card reader to Pi, configure Pi to send values to AWS
- [ ] Build data pipeline in AWS, query against student DB?
- [ ] Build web application to read from data pipeline
- [ ] Design and 3D print housing for Pi/reader
- [ ] Present?
