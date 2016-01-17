# Napkin
IoT enabled pillow

Technologies Used: Swift 2.0, Kinect 2.0, C#, Arduino, Firebase, Parse, IoT, .NET

Inspiration
Sleeping past your alarm is a struggle that plagues almost any demographic. Napkin is here to solve that.

What it does ## How we built it
We built a nap pod with various integrated features. When a user goes to sleep in the IoT nap pod, they are able to set an alarm for their intended wake up time on an iOS device. Multiple alarms are able to be set at once. When the alarm is activated, a signal is sent over a Firebase server to multiple Arduinos networked to produced a combined effect of vibrations, flashing LED lights, and motorized fly swatters on servo motors. A Kinect is then positioned to monitor the individual's eye movements. Once the Kinect recognizes that the user's eyes are opened (using Kinect 2.0), the hardware components will cease to bother the individual in the nap pod as they are successfully awake. User data is tracked on Parse servers for feedback on sleep trends available on the mobile interface.

What's next for Napkin
In future iterations, we want to bring our nap pods on the go. Individuals like long distance drivers or pilots can find themselves in dangerous situations if they fall asleep on the job. Our Kinect technology is able to detect whether an individual's eyes are open and our intuitive user interface makes it easy to incorporate the personal alarm preferences of users. We will adapt the hardware components to be more applicable to keeping individuals on the go awake.


