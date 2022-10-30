# Hire Wheels By Chirag Sardana
## Checkpoint 1 Setting Up the Project

### Using Spring Initializr

#### Output (https://start.spring.io/)

![image](/outputs/Screenshot%202022-10-25%20at%203.07.20%20PM.png)

##### Project: Maven, Language: Java, Spring Boot Version: 2.7Group: org.ncu, Artifact: hirewheels, Name: HireWheelsApplication, Description: Mini Project HireWheels Application, Package Name: org.ncu.hirewheels, Packaging: Jar, Java: 8, dependencies: ‘Spring Web’, 'Soring Data JPA’, ‘MySQL Driver', 'Spring Boot DevTools'

## Checkpoint 2 Creating Entities

## Before Creating Entity Structure is Created

![image](/outputs/Screenshot%202022-10-29%20at%2012.36.03%20PM.png)

### Entity classes in the ‘org.ncu.hirewheels.entities’ package

### Users
![image](/outputs/Screenshot%202022-10-29%20at%2012.37.39%20PM.png)
#### toString()
![image](/outputs/Screenshot%202022-10-29%20at%2012.48.19%20PM.png)
### Role
![image](/outputs/Screenshot%202022-10-29%20at%2012.38.16%20PM.png)
#### toString()
![image](/outputs/Screenshot%202022-10-29%20at%2012.50.14%20PM.png)
### Vehicle
![image](/outputs/Screenshot%202022-10-29%20at%2012.41.40%20PM.png)
#### toString()
![image](/outputs/Screenshot%202022-10-29%20at%2012.47.58%20PM.png)
### Vehicle Subcategory
![image](/outputs/Screenshot%202022-10-29%20at%2012.42.11%20PM.png)
#### toString()
![image](/outputs/Screenshot%202022-10-29%20at%2012.49.45%20PM.png)
### Vehicle Category
![image](/outputs/Screenshot%202022-10-29%20at%2012.42.32%20PM.png)
#### toString()
![image](/outputs/Screenshot%202022-10-29%20at%2012.49.33%20PM.png)
### Location
![image](/outputs/Screenshot%202022-10-29%20at%2012.42.48%20PM.png)
#### toString()
![image](/outputs/Screenshot%202022-10-29%20at%2012.49.18%20PM.png)
### FuelType
![image](/outputs/Screenshot%202022-10-29%20at%2012.43.07%20PM.png)
#### toString()
![image](/outputs/Screenshot%202022-10-29%20at%2012.49.03%20PM.png)
### City
![image](/outputs/Screenshot%202022-10-29%20at%2012.43.22%20PM.png)
#### toString()
![image](/outputs/Screenshot%202022-10-29%20at%2012.48.35%20PM.png)
### Booking
![image](/outputs/Screenshot%202022-10-29%20at%2012.43.35%20PM.png)
#### toString()
![image](/outputs/Screenshot%202022-10-29%20at%2012.47.37%20PM.png)

### **** Each Entity Contains Getter/Setters and toString() Method.****

## Checkpoint 3 Creating DAO Layer

## Classes inside ‘org.ncu.hirewheels.dao’ package

### BookingDao
![image](/outputs/Screenshot%202022-10-30%20at%206.09.55%20PM.png)
### CityDao
![image](/outputs/Screenshot%202022-10-29%20at%201.02.13%20PM.png)
### FuelTypeDao
![image](/outputs/Screenshot%202022-10-29%20at%201.02.53%20PM.png)
### LocationDao
![image](/outputs/Screenshot%202022-10-29%20at%201.03.05%20PM.png)
### RoleDao
![image](/outputs/Screenshot%202022-10-29%20at%201.04.40%20PM.png)
### UsersDao
![image](/outputs/Screenshot%202022-10-29%20at%201.05.02%20PM.png)

### VehicleCategoryDao
![image](/outputs/Screenshot%202022-10-29%20at%201.05.12%20PM.png)
### VehicleDao
![image](/outputs/Screenshot%202022-10-29%20at%201.05.49%20PM.png)
### VehicleSubcategoryDao
![image](/outputs/Screenshot%202022-10-29%20at%201.07.45%20PM.png)

## Checkpoint 4 – Establishing Relationships


### Booking and Location (Many to One)
![image](/outputs/Screenshot%202022-10-29%20at%201.18.09%20PM.png)

<br>

![image](/outputs/Screenshot%202022-10-29%20at%201.18.54%20PM.png)

### Booking and Vehicle (Many to One)
![image](/outputs/Screenshot%202022-10-29%20at%201.22.29%20PM.png)

<br>

![image](/outputs/Screenshot%202022-10-29%20at%201.23.39%20PM.png)
### Booking and User (Many to One)
![image](/outputs/Screenshot%202022-10-29%20at%201.24.17%20PM.png)

<br>

![image](/outputs/Screenshot%202022-10-29%20at%201.24.44%20PM.png)
### Location and City (Many to One)
![image](/outputs/Screenshot%202022-10-29%20at%201.51.15%20PM.png)

<br>

![image](/outputs/Screenshot%202022-10-29%20at%201.51.54%20PM.png)
### Vehicle and FuelType (Many to One)
![image](/outputs/Screenshot%202022-10-29%20at%201.52.36%20PM.png)

<br>

![image](/outputs/Screenshot%202022-10-29%20at%201.53.04%20PM.png)
### Vehicle and Location (Many to One)
![image](/outputs/Screenshot%202022-10-29%20at%201.54.37%20PM.png)

<br>

![image](/outputs/Screenshot%202022-10-29%20at%202.01.43%20PM.png)
### Vehicle and VehicleSubCategory (Many to One)
![image](/outputs/Screenshot%202022-10-29%20at%202.02.35%20PM.png)

<br>

![image](/outputs/Screenshot%202022-10-29%20at%202.03.07%20PM.png)
### VehicleSubCategory and VehicleCategory (Many to One)
![image](/outputs/Screenshot%202022-10-29%20at%202.03.50%20PM.png)

<br>

![image](/outputs/Screenshot%202022-10-29%20at%202.04.12%20PM.png)
### User and Role (Many to One)
![image](/outputs/Screenshot%202022-10-29%20at%202.05.14%20PM.png)

<br>

![image](/outputs/Screenshot%202022-10-29%20at%202.05.38%20PM.png)


### **** All relationships are bidirectional****

## Checkpoint 5 Service Layer

### Admin Service 

![image](/outputs/Screenshot%202022-10-29%20at%202.12.52%20PM.png)

### Booking Service 

![image](/outputs/Screenshot%202022-10-29%20at%207.46.10%20PM.png)

### City Service 

![image](/outputs/Screenshot%202022-10-29%20at%202.13.36%20PM.png)

### FuelType Service 

![image](/outputs/Screenshot%202022-10-29%20at%202.13.50%20PM.png)
### Location Service 

![image](/outputs/Screenshot%202022-10-29%20at%202.14.07%20PM.png)
### Role Service 

![image](/outputs/Screenshot%202022-10-29%20at%202.14.20%20PM.png)
### User Service 

![image](/outputs/Screenshot%202022-10-29%20at%207.31.40%20PM.png)
### Vehicle Category Service 

![image](/outputs/Screenshot%202022-10-29%20at%202.14.47%20PM.png)
### Vehicle Service 

![image](/outputs/Screenshot%202022-10-29%20at%202.15.35%20PM.png)
### Vehicle Subcategory Service 

![image](/outputs/Screenshot%202022-10-29%20at%202.15.04%20PM.png)


## Implmentation Part

### Admin Service Implmentation

![image](/outputs/Screenshot%202022-10-29%20at%202.33.54%20PM.png)
![image](/outputs/Screenshot%202022-10-29%20at%202.34.28%20PM.png)
![image](/outputs/Screenshot%202022-10-29%20at%202.35.34%20PM.png)
![image](/outputs/Screenshot%202022-10-29%20at%202.36.09%20PM.png)
![image](/outputs/Screenshot%202022-10-29%20at%202.36.39%20PM.png)

### Booking Service Implmentation

![image](/outputs/Screenshot%202022-10-29%20at%207.49.27%20PM.png)
![image](/outputs/Screenshot%202022-10-29%20at%207.49.43%20PM.png)
![image](/outputs/Screenshot%202022-10-29%20at%207.49.52%20PM.png)

### City Service Implmentation

![image](/outputs/Screenshot%202022-10-29%20at%202.40.07%20PM.png)

### FuelType Service Implmentation 

![image](/outputs/Screenshot%202022-10-29%20at%202.40.25%20PM.png)
### Location Service Implmentation

![image](/outputs/Screenshot%202022-10-29%20at%202.40.50%20PM.png)
![image](/outputs/Screenshot%202022-10-29%20at%202.41.02%20PM.png)
### Role Service Implmentation

![image](/outputs/Screenshot%202022-10-29%20at%202.42.15%20PM.png)
### User Service Implmentation

![image](/outputs/Screenshot%202022-10-29%20at%207.32.23%20PM.png)
![image](/outputs/Screenshot%202022-10-29%20at%207.33.00%20PM.png)
### Vehicle Category Service Implmentation

![image](/outputs/Screenshot%202022-10-29%20at%202.43.38%20PM.png)
### Vehicle Service Implmentation

![image](/outputs/Screenshot%202022-10-29%20at%202.44.04%20PM.png)

![image](/outputs/Screenshot%202022-10-29%20at%202.47.01%20PM.png)

![image](/outputs/Screenshot%202022-10-29%20at%202.47.14%20PM.png)
### Vehicle Subcategory Service Implmentation

![image](/outputs/Screenshot%202022-10-29%20at%202.48.18%20PM.png)
![image](/outputs/Screenshot%202022-10-29%20at%202.48.33%20PM.png)

## Checkpoint 6 REST Controller Layer

### Admin Controller 

![image](/outputs/Screenshot%202022-10-29%20at%202.56.22%20PM.png)

<br/>

### Booking Controller 

![image](/outputs/Screenshot%202022-10-29%20at%207.51.55%20PM.png)

<br/>

### City Controller 

![image](/outputs/Screenshot%202022-10-29%20at%202.57.35%20PM.png)

<br/>

### FuelType Controller 

![image](/outputs/Screenshot%202022-10-29%20at%202.57.55%20PM.png)

<br/>

### Location Controller 

![image](/outputs/Screenshot%202022-10-29%20at%202.58.31%20PM.png)

<br/>

### Role Controller 

![image](/outputs/Screenshot%202022-10-29%20at%202.58.47%20PM.png)

<br/>

### User Controller 

![image](/outputs/Screenshot%202022-10-29%20at%207.31.15%20PM.png)

<br/>

### Vehicle Category Controller 

![image](/outputs/Screenshot%202022-10-29%20at%202.59.32%20PM.png)

<br/>

### Vehicle Controller 

![image](/outputs/Screenshot%202022-10-29%20at%203.00.22%20PM.png)

<br/>

### Vehicle Subcategory Controller 

![image](/outputs/Screenshot%202022-10-29%20at%203.00.49%20PM.png)

<br/>

## Custom Exceptions 

### Insufficient Balance Exception

![image](/outputs/Screenshot%202022-10-29%20at%203.02.53%20PM.png)

### Location Not Found Exception

![image](/outputs/Screenshot%202022-10-29%20at%203.03.56%20PM.png)
### No Such City Exist Exception

![image](/outputs/Screenshot%202022-10-29%20at%203.04.35%20PM.png)
### No Such FuelType Exist Exception

![image](/outputs/Screenshot%202022-10-29%20at%203.13.00%20PM.png)
### No Such Location Exist Exception

![image](/outputs/Screenshot%202022-10-29%20at%203.13.35%20PM.png)
Such Subcategory Exist Exception

![image](/outputs/Screenshot%202022-10-29%20at%203.08.20%20PM.png)
### No Such Vehicle Exist Exception

![image](/outputs/Screenshot%202022-10-29%20at%203.09.07%20PM.png)
### Unauthorized User Exception

![image](/outputs/Screenshot%202022-10-29%20at%203.10.14%20PM.png)
### User AlreadyExist Exception

![image](/outputs/Screenshot%202022-10-29%20at%203.10.39%20PM.png)
### User Not AdminException

![image](/outputs/Screenshot%202022-10-29%20at%203.11.13%20PM.png)
### User Not RegisteredException

![image](/outputs/Screenshot%202022-10-29%20at%203.11.44%20PM.png)
### Vehicle Not Found Exception

![image](/outputs/Screenshot%202022-10-29%20at%203.12.08%20PM.png)

### No Such Vehicle Category Exist Exception

![image](/outputs/Screenshot%202022-10-29%20at%206.09.59%20PM.png)

### No Such Role Exist Exception

![image](/outputs/Screenshot%202022-10-29%20at%206.21.40%20PM.png)

## Some Extra POJO

### Booking User

![image](/outputs/Screenshot%202022-10-29%20at%206.11.28%20PM.png)


### Request Booking

![image](/outputs/Screenshot%202022-10-29%20at%203.16.47%20PM.png)
### Request Vehicle

![image](/outputs/Screenshot%202022-10-29%20at%203.17.39%20PM.png)
### Response Booking

![image](/outputs/Screenshot%202022-10-29%20at%203.18.15%20PM.png)
### Response City

![image](/outputs/Screenshot%202022-10-29%20at%203.18.45%20PM.png)

### Response FuelType

![image](/outputs/Screenshot%202022-10-29%20at%203.19.20%20PM.png)


### Response Location

![image](/outputs/Screenshot%202022-10-29%20at%203.19.47%20PM.png)
### Response Vehicle

![image](/outputs/Screenshot%202022-10-29%20at%203.20.24%20PM.png)
### Response Vehicle Category

![image](/outputs/Screenshot%202022-10-29%20at%203.21.02%20PM.png)
### Response Vehicle Subcategory

![image](/outputs/Screenshot%202022-10-29%20at%204.41.34%20PM.png)

### Response Vehicle With Price Per Day

![image](/outputs/Screenshot%202022-10-29%20at%204.42.29%20PM.png)
### User Login

![image](/outputs/Screenshot%202022-10-29%20at%204.43.02%20PM.png)

### Booking User

![image](/outputs/Screenshot%202022-10-29%20at%204.44.08%20PM.png)
### Vehicle Category Booking Details

![image](/outputs/Screenshot%202022-10-29%20at%204.44.42%20PM.png)


### Response User

![image](/outputs/Screenshot%202022-10-29%20at%207.29.32%20PM.png)

## Testing Part 

### Running the Application

![image](/outputs/Screenshot%202022-10-29%20at%204.51.16%20PM.png)


### Table Created in DataBase

![image](/outputs/Screenshot%202022-10-29%20at%204.53.27%20PM.png)

### Adding FuelType

![image](/outputs/Screenshot%202022-10-29%20at%205.51.12%20PM.png)

### Get All FuelType

![image](/outputs/Screenshot%202022-10-29%20at%205.52.18%20PM.png)

### Add City 

![image](/outputs/Screenshot%202022-10-29%20at%205.53.12%20PM.png)

### Get All Cities

![image](/outputs/Screenshot%202022-10-29%20at%205.54.01%20PM.png)


### Add Role 

![image](/outputs/Screenshot%202022-10-29%20at%205.55.10%20PM.png)

<br/>

![image](/outputs/Screenshot%202022-10-29%20at%205.55.46%20PM.png)

### Get All Roles

![image](/outputs/Screenshot%202022-10-29%20at%205.56.37%20PM.png)

### Add Location

![image](/outputs/Screenshot%202022-10-29%20at%205.58.23%20PM.png)

### Add Location (City Doesn't Exist)

![image](/outputs/Screenshot%202022-10-29%20at%205.59.21%20PM.png)

### Get All Locations

![image](/outputs/Screenshot%202022-10-29%20at%206.00.07%20PM.png)

### Add Vehicle Category 

![image](/outputs/Screenshot%202022-10-29%20at%206.02.29%20PM.png)

### Get All Vehicle Categories

![image](/outputs/Screenshot%202022-10-29%20at%206.03.04%20PM.png)


### Add Vehicle Subcategory

![image](/outputs/Screenshot%202022-10-29%20at%206.05.15%20PM.png)

### Add Vehicle Subcategory (Vehicle Category Doesn't Exist)

![image](/outputs/Screenshot%202022-10-29%20at%206.12.54%20PM.png)


### Get All Subcategories

![image](/outputs/Screenshot%202022-10-29%20at%206.13.27%20PM.png)

### Add User as Admin

![image](/outputs/Screenshot%202022-10-29%20at%206.17.31%20PM.png)

### Add User 

![image](/outputs/Screenshot%202022-10-29%20at%206.35.52%20PM.png)

### Add User (User Already Exist)

![image](/outputs/Screenshot%202022-10-29%20at%206.36.46%20PM.png)

### Add User (Role Doesn't Exist)

![image](/outputs/Screenshot%202022-10-29%20at%206.37.24%20PM.png)

### Login 

![image](/outputs/Screenshot%202022-10-29%20at%206.38.31%20PM.png)

### Login (Admin)

![image](/outputs/Screenshot%202022-10-29%20at%207.34.13%20PM.png)


### Login (User Doesn't Exist)

![image](/outputs/Screenshot%202022-10-29%20at%206.39.49%20PM.png)

### Login (Wrong Password)

![image](/outputs/Screenshot%202022-10-29%20at%206.40.45%20PM.png)

### Add Vehicle (Taking Input of UserName and Password to Identify whether its Admin or not i.e., User is Not Admin)

![image](/outputs/Screenshot%202022-10-29%20at%206.47.05%20PM.png)


### Add Vehicle (Vehicle Subcategory Doesn't Exist)

![image](/outputs/Screenshot%202022-10-29%20at%206.47.51%20PM.png)


### Add Vehicle (FuelType Doesn't Exist)

![image](/outputs/Screenshot%202022-10-29%20at%206.49.59%20PM.png)


### Add Vehicle (Location Doesn't Exist)

![image](/outputs/Screenshot%202022-10-29%20at%206.50.45%20PM.png)


### Add Vehicle 

![image](/outputs/Screenshot%202022-10-29%20at%206.51.37%20PM.png)


### Get All Vehicles

![image](/outputs/Screenshot%202022-10-29%20at%206.55.00%20PM.png)


### Vehicle (Current Availability Status)

![image](/outputs/Screenshot%202022-10-29%20at%207.05.30%20PM.png)

### Change Availablity Status Vehicle (User is Not Admin)


![image](/outputs/Screenshot%202022-10-29%20at%207.06.05%20PM.png)


### Change Availablity Status Vehicle (Vehicle Doesn't Exist)

![image](/outputs/Screenshot%202022-10-29%20at%207.06.38%20PM.png)


### Change Availablity Status Vehicle (User has No Rights)

![image](/outputs/Screenshot%202022-10-29%20at%207.06.38%20PM.png)


### Change Availablity Status Vehicle 

![image](/outputs/Screenshot%202022-10-29%20at%207.08.14%20PM.png)

### Vehicle (Current Availability Status)

![image](/outputs/Screenshot%202022-10-29%20at%207.08.57%20PM.png)


### Add Booking (User Doesn't Exist)

![image](/outputs/Screenshot%202022-10-29%20at%207.12.14%20PM.png)

### Add Booking (Vehicle Doesn't Exist)

![image](/outputs/Screenshot%202022-10-29%20at%207.12.47%20PM.png)

### Add Booking (Location Doesn't Exist)

![image](/outputs/Screenshot%202022-10-29%20at%207.13.13%20PM.png)


### Add Booking (Current User Balance)

![image](/outputs/Screenshot%202022-10-29%20at%207.14.38%20PM.png)

### Add Booking (Insufficient Balance)

![image](/outputs/Screenshot%202022-10-29%20at%207.18.46%20PM.png)

### Add Booking 

![image](/outputs/Screenshot%202022-10-29%20at%207.15.20%20PM.png)

### Add Booking (Current User Balance)

![image](/outputs/Screenshot%202022-10-29%20at%207.36.14%20PM.png)

### Get All Bookings

![image](/outputs/Screenshot%202022-10-29%20at%207.53.05%20PM.png)

# Completed All the Checkpoints
