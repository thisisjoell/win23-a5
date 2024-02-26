objects = main.o addition.o subtraction.o multiplication.o division.o

calculator: $(objects)
	cc -o calculator $(objects)

$(objects): %.o: %.c operations.h
	cc -c $< -o $@

clean:
	rm -f $(objects) calculator

