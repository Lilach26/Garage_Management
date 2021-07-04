# Garage_Management

Console application for Garage management, made in C# and .NET framework. Demonstrate OOP principles. 
Logic and UI are separated to ensure that in case the UI replaced, the logic remains no changes.

### Classes: ###

Ex03.GarageLogic project:

-	Vehicle – an abstract class represent vehicles
-	Car – a class represent cars, inherits from Vehicle
-	Motorcycle – a class represent motorcycles, inherits from Vehicle
-	Truck – a class represent trucks, inherits from Vehicle
-	Engine – an abstract class represent the engine of a vehicle
-	FuelEngine – a class represent Fuel-based engine, inherits from Engine
-	ElectricEngine – a class represent Electric-based engine, inherits from Engine
-	Wheel – a class represent the wheels of vehicle
-	VehicleFacroty – a class that creates any type of vehicle which supported by the garage management, when adding new type of vehicle, it can be done within minimal change
-	GarageManager – a class represent garage manager, holds methods for operations that can be done in the garage
-	ValueOutOfRangeException – a class represent exception that caused by value that out of range, inherits from the Exception class, which provided by the .NET framework.

Ex03.ConsoleUI project:
-	GarageUI – a class represent the User-Interface of the program
-	Program – a class represent the program’s entry-point, contains the “Main” method

### Enums: ###
-	eCarColor – represent the possible colors for car
-	eNumberOfDoors – represent the possible number of doors for car
-	eFuelType – represent the fuel types belongs to the FuelEngine class
-	eLicenseType – represent the license types for motorcycle
-	eVehicleGarageStatus – represent the possible status for vehicle in garage
-	eVehicleType – represent the current vehicles which supported by the garage manager
-	eMaxAirPressure – represent the maximum air pressure for each vehicle in the garage
-	eGarageOptions – represent the menu’s options in the garage management
