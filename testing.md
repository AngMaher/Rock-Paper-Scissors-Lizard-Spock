## Testing
[back to README.md](README.md)

### Developer Goals

| Developer Goals | Requirement Met |
| --- | --- |
| I want the game to be responsive so the game can be played on all devices. | Yes |
| I want the game to be clear and simple so any user can follow. | Yes |
| I wanted to have the site fun and space themed but also simple and clear to understand. | Yes |


### User Goals

| User Goals | Requirement met |
| --- | --- |
| As a User I want to know by seeing the site for the first time, know what the game is. | Yes |
| As a User I want to be able to read the rules of the game. | Yes |
| As a User I want to see clearing my choice and if I won. | Yes |
| As a User I want to be able to reset or exit the game whenever I want. | Yes |

### W3C Validator
* The HTML code passed with no errors through W3C

![htmlw3c validator](/assets/images/readme-images/HTMLW3C.png)

### CSS W3C Validator
* The CSS code passed with no errors through W3C

![cssw3c validator](/assets/images/readme-images/CSSW3C.png)

### JavaScript 
* Checked in JSHint with no errors

### Lighthouse
* Lighthouse result for main page received 100%
![lighthouse main page](/assets/images/readme-images/lighthouse.png)
* Lighthouse result for Rules page received 100%. I orginally received 87% so I changed the text colour to black and the colour of the background from a paler blue to green.
![lighthouse rules page](/assets/images/readme-images/lighthouserules.png)
* This was what the page looked like before the changes:
![rules page before the changes](/assets/images/readme-images/rules.png) 

### Responsiveness Testing
* I used Chrome Developer Tools to test for responsiveness of the website. Also tested on Firefox and safari.

### Device Testing
* I tested on multiple devices:

| Device | Screenshot |
| --- | --- |
| 17" Laptop | [screenshot laptop](/assets/images/readme-images/Laptop17.png) |
| Samgung S21 | [screenshot samsumg s21](/assets/images/readme-images/samsungs21.jpg) |
| Ipad mini | [screenshot ipad mini](/assets/images/readme-images/ipad-mini.jpg) |
| Samsung S10e | [screenshot samsumg s10e](/assets/images/readme-images/samsungs10e.jpg) |
| Iphone X | [screenshot iphone X](/assets/images/readme-images/iphonex.jpg) |
| Iphone 13 | [screenshot iphone 13](/assets/images/readme-images/iphone13.jpg) |

## Bugs

| Bugs Encountered | Fix |
| --- | --- |
|  Everytime a choice was made, the reset button and the game counter kept moving to different positions each time. | To fix this I had to change the position to absolute, and that worked. |
|  When testing the overall score, to see who won the best out of 15.  It was't working. It should have added player score and computer score.| I logged the scores to the console and the answer. I could see that a number for player was passing through ok but the value for the computer score was coming back as NaN. I was able to focus on the computer section and found it was missing a curly bracket. Once that was entered it worked. |
| In the checkOverallWinner function I have logged each one to the console to check if it is working and an error message if not. I noticed  the error message was logging to the console everytime along with the correct one. | I used and if statement for this and realised had has finished off the if statement incorrect and the error was was actually outside the if statement. Once I corrected the if statement if worked as expected. |
| Having problems with landscape on some mobiles. | Have not fixed |
| I noticed on the laptop and samsung devices the border on the buttons were black but on iphone the border was white.  | To fix this I had to give the border a colour in css |