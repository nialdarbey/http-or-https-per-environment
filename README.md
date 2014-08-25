Problem
=======

When you need to expose and consume services over plain http or https according to the environment (dev, qa, prod) then the way to proceed is

* Define spring profiles dev and prod
* Define generic endpoints with plain http and https addresses inside each profile
* Make reference to these endpoints in the flows
* Determine the profile by a runtime property to the instance of Mule, e.g. -Dspring.profiles.active=prod

Contact
=======
nial.darbey@mulesoft.com