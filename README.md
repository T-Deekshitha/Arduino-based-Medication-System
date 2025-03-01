Arduino based medication system uses Arduino to simplify medication management and ensure adherence to prescribed schedules. The system integrates an RTC (Real-Time Clock) module for precise timing, an LCD screen for user-friendly schedule setup and information display, LEDs for visualalerts, and a buzzer for audible reminders. At predefined times, the dispenser opens the compartment of the container containing the correct medicine, accompanied by notifications via LEDs and the buzzer to alert the user.

BLOCK DIAGRAM:
![image](https://github.com/user-attachments/assets/41421779-f307-4b4a-8e92-adb4c8cc0719)

MODEL:
 1. Areal time clock embedded in Arduino is used to keep track of the current time.
 2. Buzzer and LED are used to provide auditory and visual alerts to notify the
 patient when it’s time to take medication.
 3. A Servo Motor controls the mechanism that indicates correct medicine. Only the
 compartment which has correct medicine will be open and all others will be kept
 closed.
 4. An LCD Screen displays current time and message to take medicine when it is
 time to take.
 5. Timing and compartment inputs of particular medicines are taken through GPIOs
 of arduino. One input pin “confirm” is used to take these inputs. When time and
 compartment are set and confirm input is on, the system takes time input of that
 particular compartment.
 6. Areal time clock embedded in Arduino is used to keep track of the current time.
 7. Arduino is responsible for coordinating all components and executing the control
 logic.

RESULTS:

![image](https://github.com/user-attachments/assets/c703d4cc-bb8d-4fa4-af14-087239ad18f4)
LCD screen displaying current date and time in regular mode

![image](https://github.com/user-attachments/assets/0817b312-38c0-4615-a153-cb209eef4daf)
 LCD screen displaying chosen time and compartment while giving
 inputs

 ![image](https://github.com/user-attachments/assets/e1c6fc0a-c043-42e3-b164-51ecf6c42d94)
 LED blinking and buzzer sounding at the time set 

