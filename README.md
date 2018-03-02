#StarNet Converter

This project contains some simple scripts which allow me to conduct a network survey in the field using 12d field, and then get that output into StarNet for post processing. At the moment this is just working for my use case, which is: 

    1. Collect data by doing a series of station standard observations from known and unknown stations.
    2. The point ids are what are used for the final output in the CONVERTED_out.txt file. 
    3. Currently the file is then output from 12d as a report file, see the GM180213A C CON BR11 TS.rpt file for example.
        - This is going to be rewritten to deal directly with the .FLD file as the .rpt contains identical data with some extra fluff thrown in.
    4. The starnet_converter.py script is run in the directory where the .rpt file is located.
