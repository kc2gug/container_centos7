#PAPER MC

/jdk-17.0.1/bin/java -Xmx2048M -Xms2048M  -XX:+UseConcMarkSweepGC -XX:+UseParNewGC -XX:+CMSIncrementalPacing  -XX:+AggressiveOpts  -jar /minecraft/pamer_mc nogui

#DEFAULT MC

/jdk-17.0.1/bin/java -Xmx2048M -Xms2048M  -XX:+UseConcMarkSweepGC -XX:+UseParNewGC -XX:+CMSIncrementalPacing  -XX:+AggressiveOpts  -jar /minecraft/minecraft.jar nogui
