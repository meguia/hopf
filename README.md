# Hopf Fibration
Hopf fibration made in Blender with Geonodes

This is a model of the Stereographic Projection in three dimensional space of the Hopf Fibration, that describes a 3-sphere in four-dimensional space in terms of circles. Each circle is a fiber that maps to a distinct point in the ordinary 2-sphere.

![Hopf Fibration Screen Capture](Hopf_Capture.png?raw=true "Hopf Fibration")

This model make use of the new features of the geometry nodes in Blender such as repeat zones, that are only supported in version 4.0 and above. 

The control parameters of the Model are the inputs in the modifier properties of the geometry nodes:

- elevation: elevation in the 2-sphere. It goes from 0 (north pole) to 1 (south pole). The equator correspond to 0.5
- ntorus: number of paralel circles in the 2-sphere that correspond to the number of tori in the 3-sphere
- resolution: number of points for a given elevation in the 2-sphere, that corresponds to the number of rings per torus in the 3 sphere
- translation: the offset in the x coordinate of the 2-sphere for the sake of clarity of visualization
- Rotation: euler rotation of the 2-sphere. this can is keyframed with a basic animation
- angle: the maximum azimut angle in the 2-sphere. It can be useful to see how the tori are formed.

The Hopf Fibration can be visualized in a VR session (enabling the add-on 3d view: VR Scene Inspection) and/or explored in an interactive way through a MIDI Control Surface using the add-on [AddRoutes](http://www.jpfep.net/pages/addroutes/). In this last case the Blender file to be loaded is *Hopf_fibration_MIDI.blend*

  
