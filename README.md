# PC
# Language: Python
# Input: CSV (matrix)
# Output: GML (network)
# Tested with: PluMA 1.0, Python 3.6

PluMA plugin for the PC algorithm (Spirtes et al, 2000).  This plugin
wraps the source code of (Kalisch and Bhlmann, 2007), available
 at https://github.com/keiichishima/pcalg and its license in the
file LICENSE (enclosed).

The plugin takes as input a matrix in the form a CSV file.
It will then output a network (GML) in the form of a DAG, where
edges indicate causal relationships.

