# Exploring hell challenge overview

**Exploring Hell: Avoiding Obstacles on a Clockwork Rover**

> To explore the daunting surface of Venus, NASA needs an innovative obstacle avoidance sensor for its mechanical clockwork rover.

## Notes

* AREE (Automation rover for extreme environments) - new designs for the rover

* The best electronics fail around 125°C, and with Venus's average surface temperature more than 3 times that at 450°C, we need new ways to explore the surface of Venus (and possibly other planets/bodies that could have temperature extremes):
  
  * If electronics fail at a certain high point in temperature, it follows that they'd also have a "low point" where they'd fail, and that is correct (it's part of the reason that the Pathfinder/Sojurner rover died in the late '90s), so this approach will be beneficial to the exploration of bodies at both ends of the temperature spectrum, the only thing that will change is the materials that the system is made out of 

#### What we need to do

* Submit a **fully mechanical** sensor that meets the performance criteria listed below:

The sensor must respond when AREE encounters:

- Slopes greater than 30 degrees (either up or down hill)
  - Slopes less than 25 degrees must not trigger the sensor.
- Rocks greater than 0.35 meters in height
  - Sensor must not trigger for rocks smaller than 0.3 meters in height
- Holes/valleys greater than 0.35 meters deep, except for small holes which would not entrap the wheels.
  - Sensor must not trigger for holes shallower than 0.3 meters in depth
  - Holes narrower than 0.1 meters wide *may* be ignored by the sensor but it is not required to do so
  - Holes less than 0.5 meters long in the direction of travel *may* be ignored by the sensor but it is not required to do so
    - Holes greater than 0.1 meters wide and greater than 0.5 meters long and greater than 0.35 meters deep must be detected.

Additional criteria:

- Proposed technology must be designed with an anticipated operational lifespan of at least 6 months
- Some basic electrical components are acceptable: wires, resistors and inductors
  - Capacitors, microchips or diodes are not acceptable without strong and compelling evidence for their inclusion
- Limited power for the sensor is available from the turbine:
  - Average of 1W of power with a maximum of 15W on a limited basis and with justification
- Proposed sensor must be compatible with the following physical constraints:
  - Sensor must not extend more than 1m from the body of the rover, or more than 1 meter beyond the sides of the body
  - Sensor must not be more than 0.875m off the surface (note, when detecting an obstacle it may rise higher than this height)
  - Sensor must have a mass at or below 25kg
  - Proposed design must be capable of being assembled using environmentally appropriate materials
- Inputs:
  - The maximum number of inputs are one rotating shaft and two wires
    - rotating shaft may be of any size, rotated at any speed, with any amount of torque desired
    - one wire for power, one for ground/neutral; maximum voltage difference across the wires shall be 18 V or less, and a maximum current of 600 mA (i.e. essentially can be driven by 2x 9V battery)
  - Can be assumed that the rover is capable of pushing the obstacle avoidance system with 150N of force
- Outputs:
  - Obstacle detection mechanism must move a pin(s) or shaft(s) 3 cm axially, with a force of 25N
    - Current rover design specifies a single pin, however, multiple pins could be considered in order to achieve the desired performance

### Rover Specifications

- Rover body: 2.0 m by 1.2 meter rectangle
  - Wheel contact points are located on a 1.5m square
  - Ground clearance of 0.38m
- Rover wheels: 4 wheels, each 0.75m in diameter and 0.3m wide, located 1.5 m apart on center
  - All-wheel drive, only front wheels turn left/right
- Rover turbine: 2.0m diameter; 1.5m above ground clearance

## HeroX overview

> Imagine a world hot enough to turn lead into a puddle, where the atmospheric pressure can crush a nuclear-powered submarine. Now imagine sending a rover to explore that world.
> 
> Venus, ancient sister of Earth with a planetary environment just this side of hellish, has been visited by a handful of probes since the early days of space flight.  Of the many missions to our celestial neighbor, only about a dozen have made contact with the surface of the planet. The longest-lived landers only managed to function for a couple of hours before succumbing to the relentlessly oppressive heat and pressure.
> 
> Despite the punishing conditions, previous missions to Venus have nevertheless delivered important information, such as:
> 
> - Surface temperature: in excess of 450°C
> - Surface pressure: 92 times that of Earth
> - Wind speeds: 0.3 – 1.3 meters per second
>   - Due to the extreme pressure, this low wind speed feels almost like gale-force winds here on Earth
> - Length of Venusian day: 116 Earth days
> 
> [<u>NASA’s Jet Propulsion Laboratory</u>](https://www.jpl.nasa.gov/) (JPL), under a grant from the [<u>NASA Innovative Advanced Concepts</u>](https://www.nasa.gov/directorates/spacetech/niac/index.html) (NIAC) program, is studying a mission concept to return to the surface of Venus, known as the Automaton Rover for Extreme Environments ([<u>AREE</u>](https://www.nasa.gov/feature/automaton-rover-for-extreme-environments-aree)), something not accomplished since the Soviet Vega 2 landed in 1985.
> 
> Current, state-of-the-art, military-grade electronics fail at approximately 125°C, so mission scientists at JPL have taken their design cues from a different source: automatons and clockwork operations. Powered by wind, the AREE mission concept is intended to spend months, not minutes, exploring the landscape of our sister world. Built of advanced alloys, AREE will be able to collect valuable long-term longitudinal scientific data utilizing both indirect and direct sensors.
> 
> As the rover explores the surface of Venus, collecting and relaying data to an orbiter overhead, it must also detect obstacles in its path like rocks, crevices, and steep terrain. To assist AREE on its groundbreaking mission concept, JPL needs an equally groundbreaking obstacle avoidance sensor, one that does not rely on vulnerable electronic systems. For that reason, JPL is turning to the global community of innovators and inventors to design this novel avoidance sensor for AREE. JPL is interested in all approaches, regardless of technical maturity.
> 
> This sensor will be the primary mechanism by which the potential rover would detect and navigates through dangerous situations during its operational life. By sensing obstacles such as rocks, crevices, and inclines, the rover would then navigate around the obstruction, enabling the rover to continue to explore the surface of Venus and collect more observational data.
> 
> JPL has issued this Challenge to the global community because the rover must have the ability to successfully navigate in such a demanding environment in order to qualify for additional developmental funding. While the mission to the surface of Venus may be years off, the development of a suitably robust rover sensor will strengthen the case for returning to Venus with a rover, something that has never been attempted before.
> 
> What You Can Do To Cause A Breakthrough
> 
> - Click ACCEPT CHALLENGE to sign up for the challenge
> - Read the [Challenge Guidelines](https://www.herox.com/VenusRover/guidelines) to learn about the requirements and rules
> - Share this challenge. Show your friends, your family, or anyone you know who has a passion for discovery.
> - Start a conversation in our [Forum](https://www.herox.com/VenusRover/forum), or join an existing conversation, ask questions or connect with other innovators.

## Resources

* Slack: [Slack](https://acordrobotics.slack.com/archives/CS39V735K/p1586394574000500)

* Github Repo: https://github.com/acord-robotics/zooniverse/tree/areeeh --> Citizen Science Project

* Github Issues:
  
  * [IrisDroidology/Python-Learning](https://github.com/irisdroidology/python-learning/issues/18)

* Discussion: http://acord.software/stellarios/areeeh (through Disqus, Tapatalk, & Integromat)

* NASA documentation: [Automaton Rover for Extreme Environments (AREE) | NASA](https://www.nasa.gov/feature/automaton-rover-for-extreme-environments-aree/)

#### Discussion

This section is for discussions that reference AREEEH

[AC0/RD Digest · Issue #17 · acord-robotics/acord-robotics · GitHub](https://github.com/acord-robotics/acord-robotics/issues/17)

## Hardware for physical model

(Not really needed, but I thought we could possibly modify the OSR model with some tips from the AREE design schematics):

* Raspberry Pi

* ...

* [Open Source Rover Parts List](https://github.com/nasa-jpl/open-source-rover)

# Questions

* Is the entire rover mechanical? That would allow it to have a long lifetime, but how would it transmit the data/messages or receive data/messages? I'm going to look this up now
