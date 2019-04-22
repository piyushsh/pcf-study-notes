## Application Autoscaler

### PCF Study Guide Review Questions

- What is the autoscaler?
> - App Autoscaler is a marketplace service that ensures app performance and helps control the cost of running apps.
> - It allows applications to be automatically scaled
> - System load can be used as a trigger in place of manual interaction

- How would you use it?
> Add autoscaler service from market place to your space and bind it to an App and set scaling rules in your App to manage scaling.

- What can you configure?
> configure the minimum no.of instances and max no. of instances

- Do you understand autoscaler schedules?
> When there is an expected increase/decrease of traffic for the application during specific times of a day or on a particular day, it can be configured with `Scheduled Limit Changes`. For example: increasing the number of instances for Black Friday, decreasing the number of instances during off-business hours etc.,

### Pluralsight recap

- How do you handle autoscaling today? Do you autoscale?

- What 12 factor principles are important when it comes to scaling?

> Disposability

- How do you handle scaling at the data layer?

> 

### Reference

https://docs.pivotal.io/pivotalcf/1-12/appsman-services/autoscaler/using-autoscaler.html
