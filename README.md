# MCP23017_Array
This Arduino library build an massive digital input/output array from Microchip MCP23017 I2C I/O expander. By this way, up to 8 chips put on the same I2C bus can be managed as an unique device of maximum 128 I/O. Each of this ports are independents and can be manipulated like a classic Arduino pin. Interrupts features of the MCP23017 are also accesible through this library. For convenience, a batch processing mode is either available to configure all or a set of pins at the same time.

Documentation and examples (in construction) for this library are available on [the wiki of the repository](https://github.com/API-rep/MCP23017_Array/wiki#mcp23017-arduino-library-reference). Feel free to send me your corrections or misunderstand query. English is not my first language and my translations could be hazardious.

Last but not least, special thanks to:
- Douglas Gilliland and its LandBoards_Digio128V2 library who provide the base of my code.
- Limor Fried and Ladyada Adafruit_MCP23017 library for the interrupt management and much more.
