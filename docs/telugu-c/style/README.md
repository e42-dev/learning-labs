# Style

### WRONG Sample-1A
```C
#include "భవిష్యత్తులో.నేను"
START
  number_rayu(42);
  enter_kottu();
STOP
```

### WRONG Sample-1B
```C
#include "భవిష్యత్తులో.నేను"

START
  number_rayu(42);
  enter_kottu();
STOP
```
### WRONG Sample-1C
```C
#include "భవిష్యత్తులో.నేను"

START

  number_rayu(42);
  enter_kottu();
STOP
```

### CORRECT Sample-1
You need to leave empty lines before and after `START`.  
You need to leave empty line before `STOP`.
```C
#include "భవిష్యత్తులో.నేను"

START

  number_rayu(42);
  enter_kottu();

STOP
```

### WRONG Sample-2A
```C
#include "భవిష్యత్తులో.నేను"

START

number_rayu(42);
enter_kottu();

STOP
```

### WRONG Sample-2A
```C
#include "భవిష్యత్తులో.నేను"

START

  number_rayu(42);
 enter_kottu();

STOP
```

### CORRECT Sample-2
You need to **give tab-space** before each command between `START` and `STOP`.  
It is called **indentation**.
```C
#include "భవిష్యత్తులో.నేను"

START

  number_rayu(42);
  enter_kottu();

STOP
```

### WRONG Sample-3
```C
#include "భవిష్యత్తులో.నేను"

START

  send_otp("9104242425",4242);

STOP
```

## CORRECT Sample-3
You need to give a **space after comma**.  
```C
#include "భవిష్యత్తులో.నేను"

START

  send_otp("9104242425", 4242);

STOP
```

### WRONG Sample-4
```C
#include "భవిష్యత్తులో.నేను"
gaadidhaguddu sloka_rayu();
gaadidhaguddu sloka_meaning_rayu();
START
...
```

### CORRECT Sample-4
You need leave line before and after the **declarations of the new commands**.
```C
#include "భవిష్యత్తులో.నేను"

gaadidhaguddu sloka_rayu();
gaadidhaguddu sloka_meaning_rayu();

START
...
```

### WRONG Sample-5
```C
gaadidhaguddu sloka_rayu()  

{
  sentence_rayu("  Asato ma sadgamaya");
  enter_kottu();
  enter_kottu();
}
```

## CORRECT Sample-5
You should not leave an empty line.
```C
gaadidhaguddu sloka_rayu()
{
  sentence_rayu("  Asato ma sadgamaya");
  enter_kottu();
  enter_kottu();
}
```

### WRONG Sample-6A
```C
gaadidhaguddu sloka_rayu()  
{
sentence_rayu("  Asato ma sadgamaya");
enter_kottu();
enter_kottu();
}
```

### WRONG Sample-6B
```C
gaadidhaguddu sloka_rayu()  
{
  sentence_rayu("  Asato ma sadgamaya");
enter_kottu();
   enter_kottu();
}
```

## CORRECT Sample-6
You need to **give tab-space** before each command between `{` and `}`.  
That is inside the body of the function. It is called **indentation**.
```C
gaadidhaguddu sloka_rayu()
{
  sentence_rayu("  Asato ma sadgamaya");
  enter_kottu();
  enter_kottu();
}
```