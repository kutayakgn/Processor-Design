# Processor Design  
At the beginning of the project, we were expected to design and implement a processor which supports instruction set: (AND, ADD, LD, ST, ANDI, ADDI, CMP, JUMP, JE, JA, JB, JBE, JAE). Processor will have 16 bits address width and 16 bits data width. Processor will have __*5 parts*__ as follows. **Register File** will hold register values and signal to write into any register. There will be __*8 registers*__ in processor. **Instruction Memory** will be a read-only memory and instructions will be stored in this component. If the current instruction is not one of the JUMP instructions(JUMP, JE, JA etc.); the next instruction will be fetched and executed consecutively from this memory. **Data Memory** will be read-write memory which will store data. Program will be able to read data from data memory, and also store data to this memory. **Data Memory** will have __*10 bits address width*__, and 16 bits data width. **Control Unit** will produce proper signals to all datapath components. For example if the instruction is ST, control unit should produce memWrite signal which will allow Data Memory component to write data value on its data input to the address on its address input. **Arithmetic Logic Unit (ALU)** will compute arithmetic operations ADD,AND,ADDI,ANDI. Operands will be fetched from register+register or register+ immediate value. Result will be stored to the Register File. Control unit should produce proper signals to ALU according to instruction opcode (Every instruction should have distinct operational code).  
___
All other details and the report of the project are given below:  
[Details](https://github.com/erhanyalniz/Processor-Design/blob/d89bd4602010b70087831037711509e311749928/Processor%20Design%20Project.pdf)  
[Report](https://github.com/erhanyalniz/Processor-Design/blob/802fa1ca05ab1b35f8f46e567c849cdfd57cbc71/Processor%20Design%20Project%20Report.pdf)
___
> This project is a group project of 4 people.  
> Collaborators:  
> Kadir Acun  ([Profile](https://github.com/kadiracunn))
> Erhan Yalnız ([Profile](https://github.com/erhanyalniz))    
> Gökberk Çelikmasat ([Profile](https://github.com/gcelikmasat))  
> Şeref Kuray Akgün ([Profile](https://github.com/kutayakgn))  
___
