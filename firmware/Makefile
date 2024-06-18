all : flash

TARGET:=mycard

test : flash
	../../minichlink/minichlink -X ECLK:1:0:0:1:63

include ../../ch32v003fun/ch32v003fun.mk

flash : cv_flash
clean : cv_clean


