# CPNT 200 Assignment 2 Import Data into Supabase

## Edward Mah

## Postman
https://www.postman.com/avionics-architect-3156921/workspace/sait-web-dev/request/31318162-049b6819-c1ee-40c9-b4fe-60cfe8123543?ctx=documentation

## Queries
1. Get the name of every player 
  - Query: https://jllnaatnnvptedpmgiwl.supabase.co/rest/v1/RPG Players?select=name
  - ![image](https://github.com/edwardm8/cpnt-200-assign-2/blob/main/images/select-name.PNG)

2. Get name and class id of every player 
  - Query: https://jllnaatnnvptedpmgiwl.supabase.co/rest/v1/RPG Players?select=name,class_id
  - ![image](https://github.com/edwardm8/cpnt-200-assign-2/blob/main/images/select-name-and-class-id.PNG)


2. Get name and filter by race_id 1
  - Query: https://jllnaatnnvptedpmgiwl.supabase.co/rest/v1/RPG Players?race_id=eq.1&select=name 
  - ![image](https://github.com/edwardm8/cpnt-200-assign-2/blob/main/images/select-name-filter-race-id.PNG)


2. Get every player whos hp is less than 10
  - Query: https://jllnaatnnvptedpmgiwl.supabase.co/rest/v1/RPG Players?select=name,class_id
  - ![image](https://github.com/edwardm8/cpnt-200-assign-2/blob/main/images/select-all-filter-hp-lt-10.PNG)

