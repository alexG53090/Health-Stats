##Public Methods:
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
female.noActivity(female.BMR);
male.noActivity(male.BMR);
//Light Activity 
female.lightActivity(female.BMR);
male.lightActivity(male.BMR);
//Moderate Activity 
female.moderateActivity(female.BMR);
male.moderateActivity(male.BMR);
//Very Active
female.veryActive(female.BMR);
male.verActive(male.BMR)
//Extremely Active
female.extremelyActive(female.BMR);
male.extremelyActive(male.BMR);
```

#####Ideal Body Weight - IBW
```javascript
female.IBW(height);
male.IBW(height);
```

######Author: Alex Bennett
> Licesnse: MIT


