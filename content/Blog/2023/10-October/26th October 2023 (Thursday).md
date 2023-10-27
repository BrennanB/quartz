---
tags:
  - blog
  - design
  - CAD
  - Intake
  - 3Dprinting
  - driveteam
  - strategy
---

# 254 2023 Tech Binder Review

Just wanted to document a couple cool things 254 did in 2023 that may apply to us at some point in the future. Some of this is documented in their [tech binder](https://media.team254.com/2023/10/90bc07c6-2023-Tech-Binder-V6.pdf), some in their [Chief Delphi](https://media.team254.com/2023/10/90bc07c6-2023-Tech-Binder-V6.pdf) thread

## Cube Intake

![](https://i.imgur.com/va27B9c.png)


Very cool cutout into the [[Polycarbonate]] which was a light weight smart way to power the cube [[Intake|intake]] in and out. It's made out of two milled out pieces of 1/4" polycarb plates at 10DP. Not sure we could mill the same thing, but we could do a three stack of polycarb instead potentially. Then it's powered by one internal shaft going across the whole length of the robot to power both sides

## Printed Pulleys

> [!quote] [Torrance on Chief Delphi](https://www.chiefdelphi.com/t/team-254-presents-2023-breakdown-technical-binder-code-q-a/443167/6?u=brennanb)
> – This year we tried to use more aluminum pulleys because we had the teeth shear off in a printed 18T 5mm HTD pulley in our 2022 Serializer at Chezy Champs, and it was crazy hard to disassemble and swap.  
– When printing a pulley, we printed in Solid Fill and additionally added ~qty4 1/16" holes for [shear pins](https://www.mcmaster.com/90145A419/) to go between the layers

Interesting that they had teeth fail with solid fill, and then had shear pins support which we currently don't do. We haven't had teeth fail, just the flanges for holding the [[Belt]] on the actual pulley break of making the pulleys un-usable. Does make me a bit more aware that we want to test high load/hard to replace printed [[Pulleys]] extensively before going into a competition with.

## Hall Effect Sensors

> [!quote] [Torrance on Chief Delphi](https://www.chiefdelphi.com/t/team-254-presents-2023-breakdown-technical-binder-code-q-a/443167/6?u=brennanb)
>– Hall sensors are wired as a limit switch to the Falcons and serve to zero the joints  
– For the floor [[intake]] and Laterator they are on the retracted hardstop which is the starting pose  
– The elevator starts midway up with a little kickstand for faster initial auton placement, but its Hall is still at the bottom of travel so only is triggered in a floor cone pickup pose or if we lose our encoder position and want to rezero  
– Forks carriage triggers a hall when all the way climbed, to tell the motor to stop pulling

Wiring [[hall effect sensors]] directly to a [[Falcon 500|falcon]] wasn't something I was even aware of. This seems like a nice way to do it, and I assume the [[Kraken X60|kraken]] is also capable of doing this, but we should check!

Big fan of hall effects for zeroing things because there is no contact. Lets use them in 2024!

# Drive Team Filming

I want to film behind the glass for stemley and all events in the future. Team will have to invest in things to make this happen for every [[match]] so we can review it strategically and work on our communication within the [[drive team]].

-Brennan