# Cargo_Division
Software built in python to optimize the cargo distribution of a transportation company

This software was created in Python with the purpose of testing the Tkinter library and to solve a manual problem, which is the optimization of cargo distribution among trucks. It's important to note that this is a known mathematical problem called ['knapsack problem'](https://en.wikipedia.org/wiki/Knapsack_problem) that is a NP problem, and achieving a fully optimized solution is not feasible. However, for small quantities, the software can process the distribution more quickly than a human.

The distrubtion is based on the cubic meters and weight but there are also some constraints, if the destination is Tanger or Casablanca, the cargoes must go on the same truck, if possible. This constraint is added based on real-life scenarios where such arrangements are often made.

The first step is to import the Excel file containing the EXPEDITEUR (Company name), MEAD (destination), Kgs (weight), and M3 (cubic meters).
Then, it will apply the FFD algorithm to optimize the distribution and export an Excel file with a name and location chosen by the user.
