# Magic_Vlsi
the repository makes use of open source eda tools like Iverilog, Yosys , Magic_vlsi
the files are as follows:-
1)Screenshot from 2023-09-18 20-12-54.png - inverter layout snap in magic vlsi tool
2)inverter.mag - corresponding inverter magic file
3)inverter.ext- the ext file contains three kinds of information: environmental information (scaling, timestamps, etc)
for more information refer http://opencircuitdesign.com/magic/manpages/ext_manpage.html
4)inverter.spice- Convert extracted file(s) to a SPICE format file.
for more information refer http://opencircuitdesign.com/magic/manpages/ext2spice_manpage.html
5)full_adder.v and test_adder.v - the design and testbench code written in iverilog
6)full_tb.vcd- the GTK waveform corresponding to the testbench
7)yosys.png - the synthesis diagram taking full_adder.v as input
