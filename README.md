![GRBL Logo](https://github.com/gnea/gnea-Media/blob/master/Grbl%20Logo/Grbl%20Logo%20250px.png?raw=true)

***
_This is a special version with servo-like brushless ESC support_

Based on [original gnea/grbl](https://github.com/gnea/grbl) (v1.1f 328p version) and on a
interesting [fork by cprezzi](https://github.com/cprezzi/grbl-servo) for servo support.

***

- The PWM frequency is set to 490Hz (prescaler 1/128).
- The pulse width range is 1.0 - 2.0ms.
- S0 does not deactivate the PWM, but instead send min pulse width.
- Some optimization for ESC arming and correct real-time reporting.

***

Major new features in Grbl V1.1 are:
- Real-time Overrides
- Jogging Mode
- performance optimization

If you want to check a detailed changelog, please visit Grbl [original repo](https://github.com/gnea/grbl).

***

* [Licensing](https://github.com/gnea/grbl/wiki/Licensing): Grbl is free software, released under the GPLv3 license.

* For more information and help, check out grbl **[Wiki pages!](https://github.com/gnea/grbl/wiki)**

* Lead Developer: Sungeun "Sonny" Jeon, Ph.D. (USA) aka @chamnit

* Built on the wonderful Grbl v0.6 (2011) firmware written by Simen Svale Skogsrud (Norway).

* Grbl is an open-source project and fueled by the free-time of intrepid administrators and altruistic users. If you are considering a donation to help fund supporting hardware and testing equipment please visit [grbl](https://github.com/gnea/grbl) landing page and look for the **donate** button.  
Thank you!
