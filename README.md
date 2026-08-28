# OOP-Project

# MacTrack

### Nutritional Tracker App

MacTrack is a nutritional tracking application designed to help users manage their daily food intake, plan meals, and better understand their nutritional needs.

## Core Features

### 1. Meal Prepping and Planning

MacTrack will allow users to organize and plan meals in advance. Users will be able to create meals by selecting individual food items and specifying quantities or serving sizes.

Once a meal has been created, the application will calculate and display its nutritional information, including calories and macronutrients such as protein, carbohydrates, and fats.

### 2. Macro and Calorie Tracking

The application will allow users to log the foods and meals they consume throughout the day. The program will keep track of the user's total calorie intake and macronutrient intake which will provide users with an overview of their nutritional intake.

### 3. TDEE Calculator

We will include a Total Daily Energy Expenditure calculator. The calculator will use user-provided information to estimate the number of calories they typically expend in a day.

Based on the calculated TDEE, the application will provide calorie targets for different goals, such as maintaining their current weight, bulking, or cutting. These targets can then be used alongside our other features.

### 4. Food Information Tracker

MacTrack will provide users with the ability to search for individual food items and view their nutritional information. To provide a broad and reliable source of nutritional data, the application will integrate with the USDA FoodData Central API which will allow us to have data on many food products.

## How the Features Work Together

The primary purpose of MacTrack is to have these features function as parts of one big application rather than as separate small tools.

For example, a user could:

1. Calculate their TDEE and establish a calorie target based on their goal.
2. Search for foods using the FoodData Central integration.
3. Use those foods to create and plan meals.
4. Log those meals to track their daily calorie and macronutrient intake.

This allows the different features of MacTrack to work together as one nutritional tracking application.

## Example Data

```json
{
  "users": [
    {
      "id": 1,
      "name": "Alex Johnson",
      "age": 22,
      "gender": "male",
      "weight_kg": 82,
      "height_cm": 180,
      "activity_level": "moderately_active",
      "goal": "maintain",
      "estimated_tdee": 2800,
      "calorie_target": 2800
    }
  ]
}
```

## Technologies Used

* Python
* USDA FoodData Central API
* Object-Oriented Programming (OOP)


## Object-Oriented Design

MacTrack will use object-oriented programming to organize the different components of the application.

The application will use classes to represent things such as users, foods, meals, and nutritional information. These classes will allow the different features of MacTrack to work together while keeping the project organized.

## Data Management

MacTrack will store information related to:

* Users
* Food items
* Meals
* Nutritional information
* Daily food logs
* Calorie targets
* Macronutrient targets

## USDA FoodData Central

MacTrack will use the USDA FoodData Central API to provide nutritional information for food items.

The API will allow the application to search for food items and retrieve nutritional information that can be used throughout the application.

## Project Goals

The goal of MacTrack is to create a single application that combines meal planning, nutritional tracking, TDEE calculations, and food information into one system.

Rather than having each feature function as a separate tool, MacTrack will connect these features so that information from one part of the application can be used by another.

## Contributors

Braxton Hibbs

Reed Smith

Pablo Paz

Isaac Keller

```






                                                      .......                                        
                                              ........................                              
                                      ....................:--:::::........                          
                                   ......................::---:::::::..::::.                        
                                .....:::................::----:::::::::::-:::                       
                             .......:---:::.........::::::--=-::::::::::-=-:::                      
                          .........::---:::::::::::::::::--==-::::::::::==-::::                     
                         .........::----::::::::-----------==-::-------===-::::                     
                       .........:::::-----:::----==--------++-::-------==--::::                     
                      ........:::::::-----::-----===-------++-:-------+==---::                      
                     ........:::::::-------:-----==-------=*=:-------++=-----:                      
                     .......:::::::------==------==-:-----+*--------++=-------                      
                    :-=-:..:::-===------===--======-----==*=-------=*=------:                       
                    .:=+=-----====+=-=====++=======---===++-----===*=-------                        
                   ..:-=++=========+========-----==----==+=------+#=---=---                         
                   .::-=-===++====++++===----------------=-------*----=--                           
                   ::-====-==++***+========---------=------==---==-::+-                             
                   --=====++++*##+++=---:::::::::::::::-------------=-                              
                    =======+++*##+=--::::::::::::::::::::::::::::::::                               
                      ===+++*****+-::::::::::::::::::::::::::::::::::                               
                        +++++++**=:::::::::.:::::::::::::::::::::::::                .:=            
                *++            ++-:::::::......::::::::::::::::::::::             :::::-            
              *++ #*+*           ::::::::::::::::::::::::::::::::::::          -::::::-             
             #+= *++ #*+*        :::-=+****#################***+=--::        :::::::-+              
            #+=#*++#*++#**++     ==++++****************************+=    --::::::::+                
              *+= #*+ ****#+==+    ++++++++++*********************    -::::::::::=#                 
                **++#*+*#*==**--+*                                  +::::::::::+*                   
                  %#** #=++%=:::..-*                             #=:::::::::-+                      
                     *+=+#+-:::....-*                         *=::::::::::-+                        
                       #+--::... .::-*                     #-::::::::::-=                           
                          *-... ......--*                *::::::::::-=                              
                             %#*#%   #=::==+          ++=--:::::::=+                                
                                        #+=-=++    *+=:=++=+=-:-=                                   
                                           #*+==++=:-+=*%                                           
                                             *+++-=++*                                              
                                          =-:.:==*+=-====                                           
                                      =-:..:=+=*   #*+=--====                                       
                                   =-...:-+=+#        #++---=+==                                    
                               =-:...::=+=#             %++=---=++==                                
                            =-:...::-++=#                  *+=-----===--                            
                          --...:::=*=+#                      #+=-:::::-=:-                          
                         ::.:::-+*=#                            *=-:::::---                         
                          +=+**=*%                                %+--:--=                          
                            ##                                        ##%          
