# itk-snap-apptainer
ITK-SNAP (http://www.itksnap.org/pmwiki/pmwiki.php, sourceforge: https://sourceforge.net/projects/itk-snap/ ) software in apptainer

## Build

```
apptainer build ./itk-snap.sif ./itk-snap.def
```

## Start app

just run
```
./itk-snap.sif
```
to start GUI.
All app binaries are in PATH.


Tested on Rocky Linux 8, apptainer-1.2.2-1.x86_64.
