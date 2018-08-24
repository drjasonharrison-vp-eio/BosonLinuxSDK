all: *.c  ../EmulatorFiles/UART_HalfDuplex64.so
	gcc Client_API.c Client_Dispatcher.c Client_Packager.c example_linux.c Serializer_BuiltIn.c Serializer_Struct.c UART_Connector.c \
	../EmulatorFiles/UART_HalfDuplex64.so -o example_linux
