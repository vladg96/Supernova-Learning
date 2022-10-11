
# Code

---

## Button

## Live Demo

To display a live demo, use the *React Render Code* block:

```javascript  
import React from 'react';
export default function Button(props) {
 return (
   <button>
     Click me!
   </button>
 );
}  
```

## Code snippet

Display any other type of code snippet with a *Code* block:

```javascript  
import React, { useState } from 'react';
import Calendar from 'react-calendar';
import 'react-calendar/dist/Calendar.css'

export default function Component() {
  const [value, onChange] = useState(new Date());

  return (
    <div>
      <Calendar onChange={onChange} value={value} />
    </div>
  );
}  
```

```javascript  
import React, { useEffect, useState } from 'react';
import Clock from 'react-clock';
import 'react-clock/dist/Clock.css';

export default function Component() {
  const [value, setValue] = useState(new Date());

  useEffect(() => {
    const interval = setInterval(() => setValue(new Date()), 1000);

    return () => {
      clearInterval(interval);
    };
  }, []);

  return (
    <div>
      <p>Current time:</p>
      <Clock value={value} />
    </div>
  );
}  
```

```javascript  
import React, { useState } from 'react';
import Calendar from 'react-calendar';
import 'react-calendar/dist/Calendar.css'

export default function Component() {
  const [value, onChange] = useState(new Date());

  return (
    <div>
      <Calendar onChange={onChange} value={value} />
    </div>
  );
}  
```

reac

## Storybook story

Or embed a Storybook story with the *Storybook* block:

  
[Open Storybook Canvas](https://6195b518b76f57003aa69b4c-ynczzfqqyq.chromatic.com/iframe.html?addons=0&stories=0&panel=false&nav=false&id=navigation-navigation--right-click-links&full=1&viewMode=story)  


  
[Open Storybook Canvas](https://6195b518b76f57003aa69b4c-ynczzfqqyq.chromatic.com?addons=1&stories=0&panel=true&nav=false&path=%2Fstory%2Fsurfaces-modals--default)  
