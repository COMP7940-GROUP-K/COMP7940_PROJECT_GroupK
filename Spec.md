# Chatbot Design (Line Version)
### Function1: Self-assessment / Check Physical Condition
Main Process:
>>1. The user enters the keyword [Self-examination of new coronary pneumonia].
>>2. The robot sends options to chat.
>>3. The user answers the question.
>>4. The robot automatically generates a judgment and returns it to the user.
>
Optional Process:
>>4a. The user fails to send a text reply, and the robot asks him to enable the video function.
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;4b. User's symptom can not be automatically judged and the robot suggests to consult a doctor and reply hospital hotline.

### Function2: View the Epidemic Situation Map and the Number of Infected People
Main Process:
>>1. The user has his location and enters the keyword [outbreak distribution].
>>2. The robot clicks on epidemic map information.
>>3. The user clicks the confirmation to enter the link.
>>4. The user checks the epidemic information.
>
Optional Process:
>>2a. Users doesn't allow Line to open the phone location function, and the robot asks him to turn on the positioning function.

### Function3: Mask Purchase Address (2 Plans, Depending on the Situation)
#### Plan A: Locate and Navigate Routes
>
Main Process:
>>1. The user enters the latest positioning.
>
>>2. The robot recommends places and navigation routes for selling masks nearby.
>
Optional Process:
>>1a. Users doesn't allow Line to open the phone location function, and the robot asks him to turn on the positioning function.
>
>>2a. The robot recommends wrong navigation route and suggests user to switch to the third-party software to get the right navigation.
>
#### Plan B: Locate and Shopping Links
>
Main Process:
>>1. The user enters the latest positioning.
>>2. The robot shows the link to online masks provider where masks can be purchased in user's province.
>>3. The user chooses the method of delivery.
>>4. The user chooses the quantity of shopping cart.
>>5. The robot confirms the order.
>>6. The user pays for the order.
>
Optional Process:
>>3a. The user submits an excessive amount, and the robot asks him to re-enter.
>
>>3b. The user selects the delivery location beyond the original set range, and the robot asks him to prompt "switch address" or “self-collection”.
