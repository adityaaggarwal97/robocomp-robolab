# Hand Gesture Component

This Component is under development and not yet functional.


## Configuration parameters
As any other component, *HandGesture* needs a configuration file to start. In
```
etc/config
```
you can find an example of a configuration file. We can find there the following lines:
```
EXAMPLE HERE
```

## Starting the component
To avoid changing the *config* file in the repository, we can copy it to the component's home directory, so changes will remain untouched by future git pulls:

```
cd <HandGesture's path> 
```
```
cp etc/config config
```

After editing the new config file we can run the component:

```
bin/HandGesture config
```
