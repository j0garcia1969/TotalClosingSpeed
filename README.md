# TotalClosingSpeed
app to output staggered running "send off" times so that runners who run different threshold paces can race the last mile of their workouts.

Inputs are:
~average threshold pace (an average threshold pace for a 4 mile run)
Average threshold pace is defined the running pace at 85 percent of maximum heart rate. For instance if maximum heart rate is 180, then average threshold heart rate is 153. (.85 x 180 = 153).  For instance my average threshold pace is close to my 5k race pace which is 8:33 minutes per mile.
My average heart rate at this threshold pace is 155.

~base start time such that slower paces start before this time and faster paces start after this time

Average threshold pace is defined the running pace at 85 percent of maximum heart rate. For instance if maximum heart rate is 180, then average threshold heart rate is 153. (.85 x 180 = 153)

By the end of a 4 mile run, the heart rate could be 10 beats per minute higher than that at average threshold pace.

Output is a staggered start time where the runner is "sent off" from a designated start line and which produces approximately a one mile "race" to the finish line with other runners that are moving at their own average threshold pace.
