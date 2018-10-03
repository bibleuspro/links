<p>
itrs net b2b http://www.itrs2.net/ https://www.itrsgroup.com/
 <p>
 https://github.com/VLSIDA/OpenRAM
<p>
 Designs are currently being fabricated to test designs us-ing the OpenRAM framework in SCMOS
<p>
 This material is based upon work supported by the Na-tional Science Foundation under Grant No. CNS-1205685and CNS-1205493
<p>
 
 <p>
 https://www.eda.ncsu.edu/wiki/NCSU_EDA_Wiki
 <p>
  https://www.eda.ncsu.edu/wiki/FreePDK
  <p>
   OpenRAM itself is implemented in Python and is independent of commercial tools. It directly
generates SPICE, GDSII, Verilog, LEF, and Liberty (.lib) timing models. It has a simple, flexible
technology infrastructure that allows easy porting to new technologies and has been successfully
ported to MOSIS SCMOS SCN3ME (0.5 m), NCSU FreePDK (45nm), IBM CMOS 8SF, and IBM
CMOS 32nm SOI. This list contains both freely available academic processes and commercially
fabricable technologies, as well. It is distributed only with setup for the freely available academic
processes (SCMOS and FreePDK), but with little effort can be easily and readily expanded.
 <p>
 
 
 https://www.researchgate.net/publication/317055439_A_Reconfigurable_Replica_Bitline_to_Determine_Optimum_SRAM_Sense_Amplifier_Set_Time
<p>
 https://www.researchgate.net/publication/320607435_A_high_performance_multi-port_SRAM_for_low_voltage_shared_memory_systems_in_32_nm_CMOS
<p>
 https://www.researchgate.net/publication/238833010_A_15-ns_access_time_78-_mu_msup_2_memory-cell_size_64-kb_ECL-CMOS_SRAM
<p>
 https://www.researchgate.net/publication/4357663_A_07V_single-supply_SRAM_with_0495um2_cell_in_65nm_technology_utilizing_self-write-back_sense_amplifier_and_cascaded_bit_line_scheme
<p>
 https://www.researchgate.net/publication/260627238_Highly_Energy-Efficient_SRAM_With_Hierarchical_Bit_Line_Charge-Sharing_Method_Using_Non-Selected_Bit_Line_Charges
<p>
 https://www.researchgate.net/publication/3508535_A_CAD_tool_for_designing_large_fault-tolerant_VLSI_arrays
<p>
 https://www.researchgate.net/publication/2978034_1-V_10-MHz_35-mW_1-Mb_MTCMOS_SRAM_with_charge-recycling_inputoutput_buffers
<p>
 https://www.researchgate.net/publication/2976865_A_15-ns_256-kb_BiCMOS_SRAM_with_60-ps_11-K_logic_gates
<p>
 https://www.researchgate.net/project/OpenRAM-An-Open-Source-Memory-Compiler
<p>
<p>
<p>
<p>
<p><p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p><p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p><p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p><p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p><p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p><p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p><p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p><p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p><p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p><p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p>
<p><p>
<p>
<p>
<p>
<p>
 The design class also derives from a layout class (hierar-chy layout.py). The design modules in OpenRAM are derived from thedesign class (design.py). The design class has a name, aSPICE model (netlist), and a layout. Both the SPICE modeland the layout inherit their capabilities from a hierarchicalclass. The design class also provides inherited functions toperform DRC and LVS veriﬁcation of any sub-design forhierarchical debugging.The design class derives from the spice class (hierarchyspice.py) which has a data structure to maintain the circuithierarchy. This class maintains the design instances, theirpins, and their connections as well as helper functions tomaintain the structure and connectivity of the circuit hier.. 

(PDF) OpenRAM: an open-source memory compiler. Available from: https://www.researchgate.net/publication/310628824_OpenRAM_an_open-source_memory_compiler [accessed Oct 02 2018].
<p>
 SCMOS is not conﬁden-tial and an implementation using it is included, however, itdoes not include many advanced DSM design rules. Open-RAM has also been ported to other commercial technologies,but these are not directly included due to licensing issues. 

(PDF) OpenRAM: an open-source memory compiler. Available from: https://www.researchgate.net/publication/310628824_OpenRAM_an_open-source_memory_compiler [accessed Oct 02 2018].
<p>
 To facilitate user modiﬁcation and technology interoperabil-ity, OpenRAM provides a reference implementation in 45nmFreePDK45 [17] and a fabricable option using the MOSISScalable CMOS (SCMOS) design rules [13]. FreePDK45uses many design rules found in modern technologies, but isnon-fabricable, while SCMOS enables fabrication of designsusing the MOSIS foundry services. 

(PDF) OpenRAM: an open-source memory compiler. Available from: https://www.researchgate.net/publication/310628824_OpenRAM_an_open-source_memory_compiler [accessed Oct 02 2018].
<p>
s technology entered the Deep Sub-Micron (DSM) era,memory designs became one of the most challenging parts ofcircuit design due to decreasing static noise margins (SNM),increasing fabrication variability 

(PDF) OpenRAM: an open-source memory compiler. Available from: https://www.researchgate.net/publication/310628824_OpenRAM_an_open-source_memory_compiler [accessed Oct 02 2018].
<p>
 it has also been ported to several commercialtechnology nodes using a simple technology ﬁle.
<p>
nodes
<p>
reference circuit and physical implementations
<p>
he OpenRAM project aims to provide an open-sourcememory compiler development framework for memories. Itprovides reference circuit and physical implementations ina generic 45nm technology and fabricable Scalable CMOS(SCMOS) 

(PDF) OpenRAM: an open-source memory compiler. Available from: https://www.researchgate.net/publication/310628824_OpenRAM_an_open-source_memory_compiler [accessed Oct 02 2018].
<p>
 Many standard-cell ProcessDesign Kits (PDKs) are available from foundries and ven-dors, but these PDKs frequently do not come with memoryarrays or memory compilers. If a memory compiler is freelyavailable, it often only supports a generic process technol-ogy that is not fabricable. Due to academic funding restric-tions, commercial industry solutions are often not feasiblefor researchers. 

(PDF) OpenRAM: an open-source memory compiler. Available from: https://www.researchgate.net/publication/310628824_OpenRAM_an_open-source_memory_compiler [accessed Oct 02 2018].
<p>
It enables research incomputer architecture, system-on-chip design, memory cir-cuit and device research, and computer-aided design.
<p>
 fabricable memory designs
<p>
This paper introduces OpenRAM, an open-source memory compiler, that provides a platform for the generation, characterization, and verification of fabricable memory designs across various technologies , sizes, and configurations. It enables research in computer architecture, system-on-chip design, memory circuit and device research, and computer-aided design. 

(PDF) OpenRAM: an open-source memory compiler. Available from: https://www.researchgate.net/publication/310628824_OpenRAM_an_open-source_memory_compiler [accessed Oct 02 2018].
<p>
existing Process Design Kits (PDKs)
<p>

<p>
6T memoory
 <p>
  GDSII ﬁle
  <p>
   GdsMill source with OpenRAM
   
<p>
 SCN3ME_SUBM
<p>
 MOSIS Scalable CMOS
<p>
 
 
 <p>
 <p> 
  
  risc-v SCMOS openram
 <p>
 RISC vs. CISC · Analysis and Design of an Offshore .... Microcomputer and Associated Languages v vii 1-10 2. ...... Some of the memory space may be left unimplemented or open. RAM for its .... This allows the critical data from high speed RAMs to CMOS RAMs which are provided with battery back up.
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 <p>
 


The OpenRAM SRAM architecture is based on a bank ofmemory cells with peripheral circuits and control logic asillustrated in Figure 1. These are further reﬁned into eightmajor blocks: the bit-cell array, the address decoder, theword-line drivers, the column multiplexer, the pre-chargecircuitry, the sense ampliﬁer, the write drivers, and the con-trol logic.
<p>
Bit-cell Array: In the initial release of OpenRAM, the6T cell is the default memory cell because it is the mostcommonly used cell in SRAM devices. 6T cells are tiledtogether with abutting word- and bit-lines to make up thememory array. The bit-cell array’s aspect ratio is made assquare as possible using multiple columns of data words.The memory cell is a custom designed library cell for eachtechnology. Other types of memory cells, such as 7T, 8T,and 10T cells, can be used as alternatives to the 6T cell.Address Decoder: The address decoder takes the rowaddress bits as inputs and asserts the appropriate word-lineso that the correct memory cells can be read from or writtento. The address decoder is placed to the left of the memoryarray and spans the array’s vertical length. Diﬀerent typesof decoders can be used such as an included dynamic 
<p>
NANDdecoder, but OpenRAM’s default option is a hierarchical
<p>
CMOS decoder.Word-Line Driver: Word-line drivers are inserted be-tween the address decoder and the memory array as buﬀers.The word-line drivers are sized based on the width of thememory array so that they can drive the row select signalacross the bit-cell array.
<p>
Column Multiplexer: The column multiplexer is anoptional block that uses the lower address bits to select theassociated word in a row. The column mux is dynamicallygenerated and can be omitted or can have 2 or 4 inputs.Larger column muxes are possible, but are not frequentlyused in memories. There are options for a multi-level tree 

(PDF) OpenRAM: an open-source memory compiler. Available from: https://www.researchgate.net/publication/310628824_OpenRAM_an_open-source_memory_compiler [accessed Oct 02 2018].
