now:
	python3 minimax.py

oo:
	python3 oominimax.py

t1:
	make dotest NUM=1

dotest:
	python3 minimax.py < input.$(NUM) > output.$(NUM)
	diff output.$(NUM) output.$(NUM).correct
	cksum output.$(NUM)
	cksum output.$(NUM).correct
