## **High Level Test Cases**

| TEST ID  | Test case objective  | Input data  | Output data  | Actual op | Status
| -------- | -------------------- | ----------- | ------------ | --------- | ------
|  1 | Check if the BUTTTON is pressed | Program execution  | Microcontroller/Engine starts | LED ON(RED)	| PASS
|  2 | Check if the BUTTTON is pressed | Program execution | WIPER starts | LED ON(BLUE)	| PASS
|  3 | Check if the BUTTTON is pressed | Program execution | WIPER starts | LED ON(GREEN)	| PASS
|  4 | Check if the BUTTTON is pressed | Program execution | WIPER starts | LED ON(ORANGE) | PASS
|  5 | Check if the BUTTTON is pressed | - | Microcontroller/Engine stops | LED TURNED OFF | PASS

## **Low Level Test Cases**

| TEST ID  | Test case objective  | Input data  | Output data  | Actual op | Status
| -------- | -------------------- | ----------- | ------------ | --------- | ------
|  1 | Check if the BUTTTON is pressed | Program execution  | Microcontroller/Engine starts | LED ON(RED)	| PASS
|  2 | Check if the BUTTTON is pressed again | Program execution | WIPER starts and speed of wiper is slow	 | LED ON(BLUE)	| PASS
|  3 | Check if the BUTTTON is pressed again | Program execution | WIPER starts and speed of wiper is moderate	 | LED ON(GREEN)	| PASS
|  4 | Check if the BUTTTON is pressed again| Program execution | WIPER starts and speed of wiper is high	 | LED ON(ORANGE) | PASS
|  5 | Check if the BUTTTON is pressed again | - | Microcontroller/Engine stops | LED TURNED OFF | PASS
