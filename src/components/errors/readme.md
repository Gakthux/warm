# Errors


<!-- XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX -->
##Warm.errors.Simple !!$Warm.errors.Simple!!

###*Props (optionals)*
- isVisible: Boolean

> Trigger the visible or hidden classes.
> Default value is true.

- message: String

> The error message to be displayed.
> Default value is "This is an error".

- isSuccess: Boolean

> Trigger the isSuccess class.
> Default value is false.

- customClasses: String

> A string of classes you want to apply (ex : "toto foo bar")
> Default value is "".

####*Example*
```
var Warm = require('warm-react');

<Warm.errors.Simple
	isVisible="true"
	message="true"
	customClasses="toto foo bar" />
```
