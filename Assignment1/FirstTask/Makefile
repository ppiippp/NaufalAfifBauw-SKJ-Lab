# Makefile for add_numbers program

all: add_numbers run dump clean end

add_numbers: add_numbers.cpp
	g++ -o add_numbers add_numbers.cpp
	@read -p "[Enter] untuk lanjut..."

run: add_numbers
	./add_numbers
	@read -p "[Enter] untuk lanjut..."


dump: add_numbers
	objdump -d add_numbers.exe > add_numbers.asm
	@read -p "[Enter] untuk lanjut..."

clean:
	rm -f add_numbers.exe add_numbers.asm	

end:
	@echo "Selesai."
