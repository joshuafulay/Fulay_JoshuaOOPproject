I. Project Overview

GreenGrowGrid is designed to assist gardeners and agricultural interest in efficiently planning their planting layouts. The application allows users to calculate the number of plants that can be accommodated in a specified area, determine the spacing required between plants, and estimate the amount of organic fertilizer necessary for optimal growth. The user-friendly interface guides users through various calculations, making it a valuable tool for both novice and experienced gardeners.

II. OOP Principles Applied

Abstraction: The PlantCalculator class is an abstract base class that defines the common attributes and methods for calculating plant arrangements. The specific calculations for square and triangular spacing are implemented in derived classes, SquareSpacingCalculator and TriangularSpacingCalculator.

Encapsulation: The attributes such as area and spacing are encapsulated within the PlantCalculator class. They are protected, allowing only derived classes to access them directly, thus maintaining control over the data.

Inheritance: The SquareSpacingCalculator and TriangularSpacingCalculator classes inherit from the PlantCalculator class. This allows them to reuse the common code while providing their specific implementations of the calculateNumberOfPlants() method.

Polymorphism: The application demonstrates polymorphism through the use of the calculateNumberOfPlants() method. The method can be called on instances of both SquareSpacingCalculator and TriangularSpacingCalculator, allowing for dynamic method resolution based on the object type.

III. Details of the Chosen SDG and Its Integration into the Project

This project aligns with Sustainable Development Goal (SDG) 2: Zero Hunger. By providing gardeners with tools to optimize plant spacing and fertilizer usage, the application promotes sustainable agriculture practices. Efficient planting techniques can lead to better yields with minimal resource wastage, contributing to food security and sustainable land use. The application also encourages the use of organic fertilizers, which can reduce chemical runoff and promote healthier ecosystems. SDG 12: Responsible Consumption and Production, by promoting efficient use of resources such as land and organic fertilizers, the application encourages sustainable agricultural practices. It helps users minimize waste and optimize their input, leading to more responsible consumption of agricultural resources.

IV. Instructions for running the program 

This app is designed to assist you with various gardening calculations, including determining the number of plants you can fit in a given area, calculating the required area for a specific number of plants, figuring out the correct spacing between plants, and estimating the amount of organic fertilizer needed. To begin, you will navigate through a main menu where you can select from several options.

For the Calculate Number of Plants option, you’ll first choose the area unit (either Square Feet or Square Meters) and enter the area you have available for planting. Then, you’ll provide the spacing between plants in inches and select the type of spacing (Square or Triangular). The app will calculate how many plants can fit in the area based on the spacing you’ve selected. In the Calculate Area option, you’ll enter the number of plants you want to plant and the spacing between them, and the app will calculate the total area needed for those plants.

When you select Calculate Spacing, the app will allow you to enter the number of plants and the area you want to cover. It will then calculate the spacing required between plants to fit them in the area. For the Calculate Organic Fertilizer option, you’ll enter the area to be fertilized, the spacing between plants, and the type of plant (Tomato, Pepper, Lettuce, Carrot, or Cabbage). The app will then calculate the total amount of organic fertilizer required for that area and how much is needed per plant.

Additionally, the app offers spacing and fertilizer recommendations for common plants, such as Tomatoes and Peppers, to ensure optimal growth. After selecting your desired option and entering the necessary details, the app will provide accurate calculations to assist you in your gardening projects.




