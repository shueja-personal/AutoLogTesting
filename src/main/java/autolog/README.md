based on the logging framework by Oh Yes 10 FPS (https://github.com/oh-yes-0-fps/FRC2024Template/blob/swerve/src/main/java/com/igknighters/util/logging/AutoLog.java)

BENCHMARKING

1. Edit Robot.java and change `useOblog` to change between Oblog and AutoLog. Change `dataLog` when AutoLog is selected to change between logging to NT only or DataLog only. 

2. Deploy robot code (or run in simulation). The test starts automatically and prints logger update timing samples every 10 seconds, then averages those samples after 80 seconds.