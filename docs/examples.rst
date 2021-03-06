Example scripts
===============

.. _3d-directional-example:

Showing 3D Directional Sensitivity
----------------------------------

The
:download:`3d_dtcwt_directionality.py<../examples/3d_dtcwt_directionality.py>`
script in the examples directory shows how one may demonstrate the directional
sensitivity of the 3D DT-CWT complex subband coefficients. It computes
empirically the maximally sensitive directions for each subband and plots them
in an interactive figure using matplotlib. A screenshot is reproduced below:

.. image:: 3d_dtcwt_directionality.png

There are some points to note about this diagram. Each subband is labeled sich
that '1' refers to the first subband, '5' the fifth and so forth. On this
diagram the subbands are all four apart reflecting the fact that, for example,
subbands 2, 3 and 4 are positioned in the other four quadrants of the upper
hemisphere reflecting the position of subband 1. There are seven visible
subband directions in the +ve quadrant of the hemisphere and hence there are 28
directions in total over all four quadrants.

The source for the script is shown below:

.. literalinclude:: ../examples/3d_dtcwt_directionality.py
