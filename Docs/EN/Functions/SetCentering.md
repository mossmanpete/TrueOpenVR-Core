﻿# SetCentering
Centering the device (reset rotation).

С++
```c
DWORD SetCentering(
	__in int dwIndex
);
```

Delphi
```pascal
function SetCentering(
	dwIndex: integer
): DWORD;
```

#### Parameters
dwIndex - Device number, 0 - HMD, 1 and 2 - the first and second controllers.

#### Return value
If the function succeeded, the return value is 0, otherwise 1.
