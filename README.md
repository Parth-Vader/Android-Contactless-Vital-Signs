# AndroidContactlessVitalSigns

## The Code
The main code for heart rate and blood pressure is in `net/simplyadvanced/vitalsigns/bloodpressure/BloodPressureActivity.java` and `net/simplyadvanced/vitalsigns/CheckVitalSignsActivity.java`. The layout for those two can be found at `res/layout/activity_blood_pressure.xml` and `res/layout/activity_vital_signs.xml`.

The code for temperature can be `net/simplyadvanced/vitalsigns/bloodpressure/BloodPressureActivity.java` and `net/simplyadvanced/vitalsigns/bloodpressure/AddTemperatureActivity.java`. The layout for temperture can be found in `res/layout/activity_add_temperature.xml`

The other classes are mainly simulations for how they could be accomplished.

### Algorithms

To calculate blood pressure, there is [`BloodPressureActivity.setBloodPress(...)`](https://github.com/danialgoodwin/android-app-contactless-vital-signs/blob/master/app/src/main/java/net/simplyadvanced/vitalsigns/bloodpressure/BloodPressureActivity.java#L152). Unfortunately, some parts of it are hardcoded and can still be improved.

To calculate oxygen levels, there is [`OxygenSaturationActivity.calculateO2(...)`](https://github.com/danialgoodwin/android-app-contactless-vital-signs/blob/master/app/src/main/java/net/simplyadvanced/vitalsigns/oxygensaturation/OxygenSaturationActivity.java#L30).


## Test the APK
The APK to download to your Android phone can be found in the root of this directory: `app-debug.apk`.