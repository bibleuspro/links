<p>
itrs net b2b
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
<p>
<p>
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


6T memoory


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