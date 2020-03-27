# Polygon approximation for KLayout
This KLayout plugin allows to approximate all polygons in a layout by polygons with fewer vertices while respecting a maximal approximation error.

This plugin has been developed mainly for de-manhattanization of photonic structures. Layouts of photonic circuits have to be manhattanized for some fabrication processes, i.e. the layout must be converted such that it only contains horizontal and vertical polygon edges. For some usecases it is convenient to revert this manattanization.

## Usage
When properly installed in KLayout the simplification algorithm can be invoked over the menu 'Tools' -> 'Simplify Layout'.
