## Coming Soon! We are currently working on adding the code to this repository. Please stay tuned for updates! Thank you for your patience.


# Mycorrhizal Symbiosis Model

Explore the dynamics of mycorrhizal symbiosis through a bipartite network model. Investigate resource exchange between plants and fungi by simulating individuals with cooperative or defection strategies. The model incorporates reproduction and death events spanning multiple generations, providing insights into the evolutionary dynamics of this crucial ecological interaction.

## Code Versions

Both code versions share the same underlying logic and algorithm. The GUI_code is designed for initial parameter testing, allowing direct observation of the effects of changing parameter values. On the other hand, the Analysis_code is intended for running simulations multiple times.

## Installation

Build both versions (GUI_code, Analysis_code) as a usual java project. 

## Usage 

GUI_code:
This project is structured into five files, and it's crucial to refrain from making any alterations to them. Initiate the project by running MainGUI.java, which prompts the opening of a graphical user interface. Within this interface, you can conveniently set parameter values. Upon execution, the code produces the output file "results.txt" that logs simulation data encompassing population and soil properties.

Analysis_code:
This project is organized into four files, with 'Main.java' containing user specifications at the top of the file. Follow these steps to set up and run the simulation:
1. Open 'Main.java' and specify the path to the output folder at the designated user specifications section. Ensure the output folder contains subfolders named "run_1", "run_2", and so on, as indicated in 'Main.java'.
2. Include the 'initial_conditions.txt' file in the same directory where your Java files are stored.
The code generates the same output content as the Analysis_code version.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For inquiries, please contact annesophie.schwenk@gmail.com
