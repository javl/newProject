# newProject

####To do:
1. Come up with a project

####Ideas:
1. We show the sea with only pictures from social media using geolocation. Each photo is placed side by side and the sea is lineup with all the photos. It can be an installation or a website showing the coastline of Belgium and the Nederlands.

  * Other geographical lines might be interesting as well, such as borders. How far from a border do people tag/mention the country on the other side?
  * What are good places to get geolocated images from these days?

2. Data that's moves from server to server in different countries following bird routes. We can use Amazon S3 buckets to transport the data to different countries.
  * [Amazon server locations](https://aws.amazon.com/about-aws/global-infrastructure/)
  * [Cloud Flare server locations](https://www.cloudflare.com/network/)

3. Alternative ways of connecting and sending data. With standalone systems (not 'the' internet) or quirky methods.
   * Using poses / choreography / body dimensions (in VR?) to use as encryption keys. ([video](https://youtu.be/cnFBM58UOYM?t=5m5s))

4. Lately I've been coming across articles about "Post VR sadness" ([link](https://www.theatlantic.com/technology/archive/2016/12/post-vr-sadness/511232/?single_page=true)), when you leave a VR environment and are disappointed by the real world (remember how this also happened when people left the cinema after seeing Avatar?). There must be some project in this (+ I'd like to do something VR).
  * Fighting post-vr depression by making a VR experience just as boring as real life?
  * Somewhat related article on AR: [link](http://www.wired.co.uk/article/augmented-reality-environments)

5. Script that defriends terrorists (sad sad project) by using machine learning trained on terrorist pictures.
  * [Check this startup!](http://www.faception.com/) It's real!

6. Mega Panopticon
  * Getting 10+ ptz ip cameras (possibly ones with known backdoors?) and placing them so that they can see each other. By checking their orientation you should be able to make it so that clicking on a camera in one video feed makes you jump to that camera's feed.
  * Placing the cameras around a room lets you view whatever is happening from every possible angle and with different zoom levels
  * Combine with as many ways to gather data as possible
  	* Run different types of computer vision on the images (posture / face detection, etc.)
    * Sniffing wifi / bluetooth in the space
    * Let people agree to the fact that they will be filmed before entering the space by pressing their finger on a fingerprint reader?
  * Using the camera's orientation you could also interact with other objects in the space, like clicking on some device to turn it on or off
  * You'd be able to to [this](https://www.youtube.com/watch?v=qHepKd38pr00) (kind of) or [this](https://www.youtube.com/watch?v=qwNwl6Hm7zQ)

7. Variant on #6
  Creating movable camera units. For instance
    * A camera attached to a 2 meter high pole. The camera is able to move up and down (position, not pitch. Though adding pitch would be nice, but makes it extra complex), and the whole pole can rotate around its axis.
    * A camera connected to the ceiling. The camera can be lowered and the whole contraption can rotate around its axis
  The camera units are placed in a room, hallway, etc. A Vive headset in another room is tracked and its position is mapped to a position in the room of camera's. The feed of the camera that is closest to this mapped point is shown inside the headset.
  When moving around in the space, different camera feeds are shown as if you are moving in the other room. Standing up or squatting will move the camera's up and down, and roting your head / body makes the camera's rotate as well.
  The effect could be especially nice when the area covered by camera's is a lot larger than the space you move in. A small step inside your real world would be a large step inside your "ghost" world.

8. What can we do with this new repository? [wifi jammer](https://github.com/DanMcInerney/wifijammer)
  * You can use it [for rickrolling](https://www.wired.com/2014/07/rickroll-innocent-televisions-with-this-google-chromecast-hack/)

9. Your Tweets impressions VS real conversations


####Interesting links:
* [Border Bumping](http://borderbumping.net/) moves country borders on a map based on what celltower you are connected to in the border area.
* [Border Check](http://roelof.info/projects/(2013)Border_Check/) is a browser plugin that maps internet infrastructure, showing how your data gets routed through the world.
* Just for fun: border-wise [Baarle-Nassau / Baarle-Hertog](https://www.google.nl/maps/@51.4362036,4.9338757,14z) is an interesting area, with parts of the Netherlands within parts of Belgium, within the Netherlands.
