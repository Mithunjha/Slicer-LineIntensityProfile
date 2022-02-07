cmake_minimum_required(VERSION 3.13.4)

project(SlicerExtension)

#-----------------------------------------------------------------------------
# Extension meta-information
set(EXTENSION_HOMEPAGE "https://www.slicer.org/wiki/Documentation/Nightly/Extensions/SlicerExtension")
set(EXTENSION_CATEGORY "Learning")
set(EXTENSION_CONTRIBUTORS "Mithunjha (University of Moratuwa)")
set(EXTENSION_DESCRIPTION "This extension deveoped for Medical Image Processing Module")
set(EXTENSION_ICONURL "http://www.example.com/Slicer/Extensions/SlicerExtension.png")
set(EXTENSION_SCREENSHOTURLS "http://www.example.com/Slicer/Extensions/SlicerExtension/Screenshots/1.png")
set(EXTENSION_DEPENDS "NA") # Specified as a list or "NA" if no dependencies

#-----------------------------------------------------------------------------
# Extension dependencies
find_package(Slicer REQUIRED)
include(${Slicer_USE_FILE})

#-----------------------------------------------------------------------------
# Extension modules
add_subdirectory(LineIntensityProfile)
## NEXT_MODULE

#-----------------------------------------------------------------------------
include(${Slicer_EXTENSION_GENERATE_CONFIG})
include(${Slicer_EXTENSION_CPACK})
