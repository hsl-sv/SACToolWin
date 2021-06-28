CFLAGS = -Wall

all: sac2col sacch saclh sacmax clean

sac2col: sac2col.o sacio.o
	$(CC) -o /home/skycr/sactool/$@ $^

sacch: sacch.o sacio.o datetime.o
	$(CC) -o /home/skycr/sactool/$@ $^ -lm

saclh: saclh.o sacio.o
	$(CC) -o /home/skycr/sactool/$@ $^

sacmax: sacmax.o sacio.o
	$(CC) -o /home/skycr/sactool/$@ $^

clean:
	rm *.o
