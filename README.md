##Public Methods
#####Body Masss Index - BMI
```javascript
female.BMI(weight, height);
male.BMI(weight, height);
```
#####Basal Metabolic Rate - BMR
>The amount of calories you need to
maintain body weight.
```javascript
female.BMR(weight, height, age);
male.BMR(weight, height, age);
```

######BMR by lifestyle:

> In order to call the following methods, you must first set a BMR value, or else you must pass a BMR value manually.
``` javascript
//Sedentary 
female.noActivity(BMR);
male.noActivity(BMR);
//Light Activity 
female.lightActivity(BMR);
male.lightActivity(BMR);
//Moderate Activity 
female.moderateActivity(BMR);
male.moderateActivity(BMR);
//Very Active
female.veryActive(BMR);
male.verActive(BMR)
//Extremely Active
female.extremelyActive(BMR);
male.extremelyActive(BMR);
```

#####Ideal Body Weight - IBW
```javascript
female.IBW(height);
male.IBW(height);
```

######Author: Alex Bennett
> Licesnse: MIT


