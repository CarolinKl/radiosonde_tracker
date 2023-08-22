# radiosonde_tracker
This repository contains code for reconstructing the position of radiosondes from multiple RNO-G phased arrays of radio antennas in the ice 

# Link to thesis
The corresponding thesis will be available at https://ecap.nat.fau.de/index.php/research/publications/theses/

# Contents
The file important_functions includes functions to calculate the angle between the radiosonde and the different stations. A function to calculate the expected angle at the phased array based on the angle between radiosonde and station is also implemented. Furthermore, the code provides functions to reconstruct the angle at the phased array based on the incoming radio signal (phasing). A calculation of the surface interaction point using the angle at the phased array is also included. Finally, the code for two different chi^2 minimizations reconstructing the radiosonde position is provided. A detailed docstring documentation of the functions will be added in the future.
