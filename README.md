# Cargo_Division
Software built in python to optimize the cargo distribution of a transportation company

This software was created in Python with the purpose of testing the Tkinter library and to solve a manual problem, which is the optimization of cargo distribution among trucks. It's important to note that this is a known mathematical problem called ['knapsack problem'](https://en.wikipedia.org/wiki/Knapsack_problem) which belongs to the NP problem class. Achieving a fully optimized solution is not feasible. Nevertheless, for small quantities, the software can process the distribution more quickly than a human.

The distrubtion is based on the cubic meters and weight but there are also some constraints, if the destination is Tanger or Casablanca, the cargoes must go on the same truck, if possible. This constraint is added based on real-life scenarios where such arrangements are often made.

The first step is to import the Excel file containing the EXPEDITEUR (Company name), MEAD (destination), Kgs (weight), and M3 (cubic meters).
Then, it will apply the [FFD algorithm](https://en.wikipedia.org/wiki/First-fit-decreasing_bin_packing) to optimize the distribution and export an Excel file with a name and location chosen by the user.

__Excel for importation:__

![cargo_file](https://github.com/RicardoFamiliar/Cargo_Division/assets/117604174/758f24b1-f814-4e58-a6e7-e2defe173b48)

__Interface (with a theme changer available on tkinter library):__

![interface](https://github.com/RicardoFamiliar/Cargo_Division/assets/117604174/5d620df7-f5b7-49c9-9335-dd5aaaa78acf)

__Final result:__

![cargo_final](https://github.com/RicardoFamiliar/Cargo_Division/assets/117604174/52b7ec6f-d8d9-43e0-8489-ceba6223aa91)

(the company names are fictitious and i used 25000 kg's and 70 Cubic Meters as an example)

I've uploaded the code and the Excel test file for you to check out, to make the executable you must run __'pyinstaller --onefile (name of the file with the code i showed you).pyw'__ 
Don't hesitate to share any recommendations or thoughts! 😄
