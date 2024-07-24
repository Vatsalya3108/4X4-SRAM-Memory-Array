# 4X4-SRAM-Memory-Array
Link to ppt : https://docs.google.com/presentation/d/1VH6vMjZ9fI4u3cm4yrX-GekgR82bWQu_/edit?usp=sharing&ouid=106454815770425673878&rtpof=true&sd=true
## Introduction 
A 4x4 SRAM (Static Random-Access Memory) memory array consists of 16 memory cells arranged in a grid with 4 rows and 4 columns. Each cell in the array can store one bit of data, resulting in a total capacity of 16 bits. Here are some key points about a 4x4 SRAM memory array:

### Structure:
1. **Memory Cells**: Each cell typically consists of six transistors (6T) that form a bistable flip-flop circuit to store a single bit of data. The 6T design is preferred for its balance between speed, stability, and area efficiency.
2. **Row and Column Lines**: The array has word lines (WL) and bit lines (BL). Word lines run horizontally and select the rows, while bit lines run vertically and are used for reading and writing data.
3. **Word Lines**: Four word lines correspond to the four rows, activated one at a time during read or write operations.
4. **Bit Lines**: Four pairs of bit lines correspond to the four columns, used to sense or drive the data into the cells.

### Operations:
1. **Read Operation**: To read data, the word line for the desired row is activated, connecting the selected row of memory cells to their corresponding bit lines. The bit lines are pre-charged to a specific voltage, and the stored data in the selected cells alter this voltage, which is then sensed by sense amplifiers.
2. **Write Operation**: During a write operation, the word line for the desired row is activated. The new data is driven onto the bit lines, overwriting the existing data in the selected cells.
3. **Pre-Charge**: Before a read operation, bit lines are pre-charged to a known state to ensure accurate reading.

### Addressing:
1. **Address Lines**: To access specific bits within the array, address lines are used. In a 4x4 array, 2 address lines are sufficient to select one of the 4 rows, and another 2 address lines to select one of the 4 columns.

### Advantages:
1. **Speed**: SRAM is faster than other types of memory like DRAM due to its simpler design and lack of refresh requirements.
2. **Stability**: SRAM retains data as long as power is supplied, making it suitable for cache memory and other high-speed applications.

### Disadvantages:
1. **Power Consumption**: SRAM consumes more power than DRAM because it uses more transistors per cell.
2. **Area**: SRAM cells occupy more space on the silicon wafer compared to DRAM cells, which can limit the density of the memory array.

Overall, a 4x4 SRAM memory array is a fundamental building block used in various digital circuits, providing fast and reliable storage for small amounts of data.
