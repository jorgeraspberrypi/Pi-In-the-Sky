# Pi-In-the-Sky
#Code
Code can be found here: https://github.com/jorgeraspberrypi/Engineering_4_Notebook/blob/master/Python/PIintheSky.py
# Timeline
We were able to finish SoliWorks, print it out and put it together fairly quickly. We spent about two weeks working on the actual rocket.
However, the code had slowed us down a bit in our schedule. Some of it was easy because wer already had code for it, but we had some trouble trying to figure out how to collect the data of the accelerometer. As well we had forgotten how to power the pi wirelessly.
We ended up doing the code at the end and finished everything else like printing out the rocket and assembling the launch part before completing the code.
# Pictures
  ![Picture](rocketbottom.JPG) ![Picture](rocketophalf.JPG) ![Picture](rockettop.JPG) ![Picutre](rocketfins.JPG) ![Picture](rocketfins.JPG) 
  ![Picture](angle1.JPG) ![Picture](angle2.JPG) ![Picture](angle3.JPG)
#Results
  ![Picture](Piintheskydatacharts.JPG)
These were two seperate launches that we performed and both clearly had rather different results. The first one even we had trouble interpreting because the ammount of change in the direction of the graph is very random. Because we had such a hard time evebn getting data, we didn't know which files exactly lined up with what flight. For the first we belive it may have been on of our tests where we just threw the pi up to test on Dr.Sheilds' phone. The second one we belive to have been one of our actual rocket launches. So the naturaly the big arc is the launch and the plateu at the end is when the rocket was caught and held. After many confusing launches we finally got this data. Our pi had not been creating the data file when we launched it even though it had worked when hooked up to the computer. Dr.Shields told us that this had happened to a previous student and they couldn't figure it out either. We had Dr. Shields use an SSH connection to collect the data as if it were connected to the computer. 
Listed data for flight 1 can be found here: https://github.com/jorgeraspberrypi/Engineering_4_Notebook/blob/master/Python/flightdata2019-06-06%2013:11:19.794460.txt
Listed data for flight 2 can be found here: https://github.com/jorgeraspberrypi/Engineering_4_Notebook/blob/master/Python/flightdata2019-06-06%2013:17:41.093250.txt
#Things we changed
We ended up adding an LED to determine when the pi would start collecting data. We also added a two minute delay at the beginning but later changed it when we had problems with the pi collecting data and we stwtched to controlling it with an SSH connection. We also used two 1 liter bottles instead of a 2 liter on because that's what we had.
 #Lessons learned
 We learned a lot of leasons through this project. Most importantly that we should always ask questions. For much of the time we didn't want to ask anyone for help so we ended up being stuck on little things for a long time. We also learned that sometimes things just don't work. We had so much trouble trying to get our pi to collect the data not attatched to the pi and none of us, not even Dr. Shields knew how to fix it. And when it became clear that that would not work we found a way to complete the project.
