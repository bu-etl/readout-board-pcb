
.PHONY: diagrams

diagrams:
		draw.io -s 2 -p 0 -x -f png -o data-flow.png etl-readout-board.drawio
		draw.io -s 2 -p 1 -x -f png -o power-distribution.png etl-readout-board.drawio
		draw.io -s 2 -p 2 -x -f png -o ctrl-and-mon.png etl-readout-board.drawio

		draw.io -p 0 -x -f pdf -o data-flow.pdf etl-readout-board.drawio
		draw.io -p 1 -x -f pdf -o power-distribution.pdf etl-readout-board.drawio
		draw.io -p 2 -x -f pdf -o ctrl-and-mon.pdf etl-readout-board.drawio

clean: data-flow.png power-distribution.png ctrl-and-mon.png data-flow.pdf power-distribution.pdf ctrl-and-mon.pdf
