# Modelling-Simulation-and-Optimisation
Part 1 Simulation: 

Create a simulation for the London Old Oak Commons to Birmingham Interchange section of the high-speed line. The distance between London Old Oak Common Station and Birmingham Interchange Station is 145km. Assume that the track consists of k signalling blocks of equal length and that a fixed train schedule of n trains per hour is to be used.Verify the simulation model by inducing a temporary break down due to electrical malfunction of the 9am train from London to Birmingham. It takes 30 minutes to fix the
problem. To reflect operational conditions introduce variability of travelling times using a suitable distribution on events. You can choose the distribution and the parameters as you deem appropriate. It may be useful to consider two types of variations: normal deviations (of just a few minutes for example caused by common weather events or delays in departure due to passenger movements), and rare events with bigger impact (like heavy rain or technical problems) that may impact also on later trains. Yuxiang Yang et al [1] report a log-normal distribution with μ= 3.378 and σ=0.751 for the delay times (in minutes( on a segment of a comparable Chinese high-speed train (including the knock-on effect on the following trains).

Part 2 Optimisation:

For given parameters k and n create a train schedule that sets out the departure and
arrival time for trains with the first train leaving at 7am and the last train leaving at 10pm.
Using the simulation created in part 1 report the distribution of actual delay times. The aim
is to maximise the number of trains operating per hour under the constraint that the
average delay time should not be higher than half the scheduled time between consecutive
trains. Report your recommendation for the layout of the track (k) and the schedule (n).
