# LEC_benchmarks
AIGs and a script for building LEC instances on them.

Directory AIGs contains default AIGs in a text format.

Directury CNFs contains original LEC problems in CNF format and obtained versions after DJD-preprocessing with best founded variable order for every CNF. 

The script LEC_by_two_circuits.py builds a LEC in CNF format from two AIGs in ".aag" extension (ASCII). 
Example:
python LEC_by_two_circuits.py -nf ./AIGs/dadda16x16.aag -ns ./AIGs/column16x16.aag -o DvC_16x16.cnf

If your AIGs are in binary form, they can be converted to text using the Armin Biere app: https://github.com/arminbiere/aiger

If you want to construct new AIGs, you can use Transalg tool for it: https://gitlab.com/transalg/transalg

