# 'Mr. Roboger's Neighborhood'

JS Web Application by Henry Oberholtzer

##### Describe countUp()
Test: Returns an array counting up by integers starting at 0 to the user's given number
Code: countUp(5)
Result: [0, 1, 2, 3, 4, 5]

##### Describe numberReplacer()
Test: If a number contains the digit 3, replace with the string "Won't you be my neighbor?"
Code: numberReplacer()

Test: If a number contains the digit 2, and no 3, replace with the string "Boop!"
Code: numberReplacer(21)
Result: "Boop!"

Test: If a number contains the digit 1, and no 2 or 3, replace with the string "Beep!"
Code: numberReplacer(11)
Result: "Beep!"

##### Describe arrayReplacer()
Test: Iterates through an array, replacing digits as needed with numberReplacer()
Code: numberReplacer([1, 2, 4, 21, 11, 13, 30])
Result: ["Beep!", "Boop", 4, "Boop!", "Beep!", "Won't you be my neigbhor?", "Won't you be my neighbor?"]

##### Describe mrRobogerSystem()
Test: Takes a single digit input, returning an array counting up from zero, which has been transformed according to the protocol from arrayReplacer()
Code: mrRobogerSystem(13)
Result: [0, "Beep!", "Boop!", "Won't you be my neighbor?", 4, 5, 6, 7, 8, 9, "Beep!", "Beep!", "Boop!", "Won't you be my neighbor?"]
