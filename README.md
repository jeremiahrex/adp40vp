# Delta ADP-40VP Rev A
 This project is a reverse engineered version of the Delta ADP-40VP Rev A switching power supply. This power supply is used in many Dell PowerConnect network switches. This example came from a PowerConnect 2716. I created this project because two of these supplies had died within 2 years and I knew other people who had theirs fail and wanted to be able to troubleshoot the complex design.

# What's included
Principly, a schematic and PCB layout with correct components. All connections are verified visually and by continutity. Some datasheets are included.

 ## What isn't right?
 A lot! You can't use this to fabricate the design. It's for troubleshooting reference only. Here's a list:

 1. There are no values.
 1. Most components are close, especially the ICs which are correct family, but in most cases aren't the exact part number. Lots of the top side component sizes aren't very close either, I was focused on lead pitch only.
 1. Don't turn on the silk layer unless you want your eyes to bleed.
 1. The heatsink is hilariously incorrect, but it already existed so eh.