wallHeatFluxIncompressible
==========================

Utility originally by the forum member Eelco van Vliet, for OpenFOAM 2.1.0: http://www.cfd-online.com/Forums/openfoam-post-processing/101972-wallheatflux-utility-incompressible-case.html#post368330

It's the one provided in the branch `OF21x`.

This git repository further adapts the utility for OpenFOAM 2.2.x and 2.3.x, done by Bruno Santos (wyldckat@github).
Then further adapted by Bruno Santos as well for blueCFD-Core 2.3-1.

WARNING: If you're planning on using OpenFOAM 2.2.0, then use the branch `OF21x`.


License
=======

The same as OpenFOAM(R), namely GNU GPL v3. For more information, see the file LICENSE.


Building on blueCFD-Core 2.3-1
==============================

Using Git
---------

  1. Go to your user folder:

     ```
     mkdir -p $FOAM_RUN
     cd $FOAM_RUN/..
     ```

  2. Clone the repository and go into the cloned repository:

     ```
     git clone https://github.com/blueCFD/wallHeatFluxIncompressible.git
     cd wallHeatFluxIncompressible
     ```

  3. Checkout the repository respective to the version of OpenFOAM you are using:

   * blueCFD-Core 2.3-1:

     ```
     git checkout blueCFD-Core-2.3-1
     ```

   4. Build `wallHeatFluxIncompressible` by running:

     ```
     ./Allwmake
     ```


Using Zip
---------

  1. Go to your user folder:

     ```
     mkdir -p $FOAM_RUN
     cd $FOAM_RUN/..
     ```

  2. Get the Zip file for the repository respective to the version of OpenFOAM you are using:

   * blueCFD-Core 2.3-1:

     ```
     wget https://github.com/blueCFD/wallHeatFluxIncompressible/archive/blueCFD-Core-2.3-1.zip
     ```

   3. Unzip the respective file and go into the respective folder, for example:

     ```
     unzip blueCFD-Core-2.3-1.zip
     cd wallHeatFluxIncompressible-blueCFD-Core-2.3-1
     ```
     
   4. Build `wallHeatFluxIncompressible` by running:

     ```
     ./Allwmake
     ```
