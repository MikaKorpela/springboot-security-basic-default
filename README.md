# springboot-security-default #

The ```spring-boot-starter-security``` dependency enables the authentication and authorization in all end-points.

The default security configuration creates one user with username ```user``` and a random password. The password is printed in the console when the application starts.

```terminaloutput
2025-04-28T12:53:35.287+03:00  WARN 21644 --- [springboot-security-basic-default] [           main] .s.s.UserDetailsServiceAutoConfiguration : 

Using generated security password: 6eb39310-ba37-419e-87b8-27531ea7cdf6

This generated password is for development use only. Your security configuration must be updated before running your application in production.

```


The default security configuration does not include any settings for authorization.
