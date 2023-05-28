# Data Description
Measurements of line pressure and fluid temperature before and after the block are taken, the temperature of the copper block, and eleven different streamwise temperature profiles between the copper block and cold plate in order to calculate the convective heat transfer coefficient along the cold plate from the sCO2. Data is taken at 12 different chiller temperatures to perform a temperature sweep to ensure supercriticality is reached. There are three different datasets involved in my research. Dynamic and static data are generally collected in a similar way, both using sensors like thermocouples, coliolis meter, pressure transducers, and readings given by operating devices. These sensors are plugged into a DAC card and read through LabVIEW to be later collected and placed into an excel spreadsheet. Mapped data differs from dynamic and static data in that it is collected using a mapped array of single temperatures spaced along a wire, which is then routed through the cold plate to generate a map. The software attached to this sensor is called ODiSI and generates a temperature profile in the streamwise direction of CO2 flow. Below are the categories for datatypes: <br />

<br /> Dynamic Data:
* inlet/outlet temperature
* inlet/outlet pressure
* Mass flow rate
* Density
* Block Temperature

<br /> Static Data:
* Pump speed 
* Chiller mass flow rate
* Chiller inlet temperature

<br /> Mapped Data:
* LUNA fiber temperature sensor

# Roles and responsibilities 
The data management roles for the project defined in DMP 1 are primarily handled by myself and another researcher working on a similar project on the same test setup. Roles that can be split between the projects (e.g. those that involve both projects) are split between myself and the other graduate researcher, such as instrumentation maintenance, quality control, experimental setup construction, DMP implementation, access control, and software creation. The rest of the roles are fulfilled by the individual researcher as it pertains to their own project. Roles such as archiving, data manager, protection of sensitive data, data organization, metadata generation, and data analysis are handled on a per-project basis. Another role outside of the ones discussed in the previous class specific to this project includes safety checks. As both I and the other researcher are investigating supercritical fluids at high pressures and temperatures, it’s important that both of us maintain constant checks on our work to ensure that the quality of our work and the equipment being used will hold up to the safety standards of the lab we operate in. 

# Data standards and metadata
# Storage and security 
The data I am collecting is being used by a private company in the development of a cooling system for a grant project, and therefore falls under OSU’s definition of sensitive data. This means that data collected for this project must be protected to a reasonable degree and must not be exposed to the public before an internal company review. Data for this project is stored and collected on lab computers, while collective data about the line setup and components between the line are stored on a shared box with the other graduate researcher using the same test setup. <br />
During the project, data related to the results of the project are stored locally on a machine located in the locked laboratory where the project is being worked. This ensures that the data has no chance of being disseminated 	before its intended release. This, of course, lends itself to being easily wiped if the hard drive used to store the data decides to randomly corrupt. To prevent this, an external flash drive is used to store the data as a separate digital copy apart from the one stored locally. This process requires uploading each file manually, and therefore has the potential to loose files due to forgetting to place an extra copy in the drive.

# Access and data sharing
Sharing data is important to advance research in a collaborative effort between researchers. There are, however, important caveats that require data be stored securely or strictly internally such as NDA agreements on data or other confidential aspects of research for private companies/institutions. The project that I am currently working on requires it be kept internal to the project sponsor, which means data collected over the course of the project will be kept private until a limited release is approved. This limited release can include conclusions and methods, along with the metadata affiliated with them. <br /> 
To ensure this data stays preserved for future use, two copies are created on physical devices/drives. All data and processes used to collect the data are stored locally on a computer that can only be accessed by myself, as well as a separate physical drive that is archived with other previous work done in the lab. These archived projects are kept for a period of 5 years before they are reorganized to make space for new projects. Organization inside the project files then is key to ensure that reproducibility is possible in the future. A document is included with instructions on how to reproduce the experiment, as well as detailed metadata associated with how each variable is included in the project files. The space where the storage drives are held is locked until access is given by the PI. The files that are preserved in project files can vary due to the different software that is employed from project to project. For this research, there are six main project file types: 
1.	Matlab code 
2.	LabVIEW case files
3.	Excel spreadsheets
4.	PDF documents 
5.	JPEG files
6.	LunaFiber case downloads <br />
Many of these files are accessed only through proprietary software that requires money to access. Matlab, LabVIEW, and LunaFiber ODISI program files require software subscriptions and unfortunately cannot be changed to any other format. This, of course, can be remedied by including descriptions of their purpose and an instructional guide as to how they can be created on other software, however in the long run this damages the project’s ability to be shared between platforms. 

# Archiving and preservation
