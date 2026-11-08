# Blender 5 Fixes #

This fixes the addon for Blender 5. Based on a fork that fixed it for Blender 4. Quite untested but for my use case in World at War which was rigging models and animating a gun it worked well.
+ [Download Addon here](https://github.com/notrickzdumbo/blender5-cod/releases)

Known unfixed/broken/bugged things:

+ Exporting notetracks as a separate file (.NT_EXPORT) breaks the xanim exported alongside it. Just keep that ticked off or work around it.
 
 # ![Blender-CoD logo](https://raw.githubusercontent.com/CoDEmanX/blender-cod/master/blender-cod-logo.png) Blender-CoD (Old Description) #
*Blender Add-On for Call of Duty® modding*

Import / export addon for Call of Duty's intermediate model and animation plaintext file formats - no Maya required.

**Download**:  Several download options are available. Choose one of the following:
+ [Official releases]
+ [Experimental]
+ Checkout with Git

Model, animation and notetrack export to any CoD title:
  * XMODEL_EXPORT v5 (vCoD, CoD:UO)
  * XMODEL_EXPORT v6 (CoD2-CoD7)
  * XANIM_EXPORT v3 (all)
  * NT_EXPORT (CoD5, CoD7)

Use in combination with [Lemon / Lime](http://tom-crowley.co.uk/downloads/) or [Wraith](http://aviacreations.com/wraith/).<br>


***Note: Feature description not up-to-date!***

Experimental import is available for XMODEL_EXPORT v6, but lacks materials, UV mapping etc. Armatures may be imported wrong, weights aren't handled yet.

Original export scripts for Blender 2.4x by Flybynyt<br>
Rewritten scripts for Blender 2.5x and above by CoDEmanX<br>
Contributions by SE2Dev

*2015-05-05: Migrated project from Google Code Project Hosting to GitHub. Addon releases were downloaded 4232x at that time.*

## Introduction ##

Getting new 3D content into Call of Duty games can be expensive, because the official mod tools only include plugins for the commercial 3d modelling software [Maya](http://www.autodesk.com/products/maya/overview) by Autodesk (former Alias). With this addon, you can do it for free!

Blender-CoD is a **free**, **open-source** project and provides a plugin for the as well free and open-source **3D modelling software [Blender](http://www.blender.org/)**.

It adds support for XMODEL_EXPORT v5/v6 and XANIM_EXPORT v3 formats, which can be compiled to xmodels and xanims using the mod tools. All CoD titles are supported for export (Blender -> Asset Manager -> Call of Duty).

You can basically import any supported 3d model into Blender (e.g. Blender files, Wavefront OBJ, Collada DAE, 3ds Max 3DS and more), edit it and finally export it for CoD using the Blender-CoD Add-On.

## Features ##

**Supported CoD-titles** (export only):
  * CoD1 (vCoD)
  * CoD:UO (United Offensive)
  * CoD2
  * CoD4 (Modern Warfare)
  * CoD5 (World at War)
  * CoD7 (Black Ops)


### XMODEL_EXPORT v5/v6 ###
  * Supports mesh export with automatic triangulation
  * Armature export (bones)
  * Vertex colors (v6 only, optionally: use color as alpha)
  * Mesh modifiers except Armature (optional)
  * Armature animation (poses) to xmodel sequences ("Pose animation")
  * Adjustable minimum bone weight (optional)
  * Vertex clean-up (optional)
  * User Interface: File > Export > CoD Xmodel (.XMODEL\_EXPORT)


### XANIM_EXPORT v3 ###
  * Supports armature animation export
  * Frame range and framerate can be specified
  * Notetrack export for all CoD titles (minds frame range settings)
  * User Interface: File > Export > CoD Xanim (.XANIM\_EXPORT)
  

