# # -*- Mode: python; py-indent-offset: 4; indent-tabs-mode: nil; coding: utf-8; -*-

# def build(bld):

#     obj = bld.create_ns3_program('vehicular-simple-one', ['millicar','core', 'propagation', 'spectrum', 'mmwave'])
#     obj.source = 'vehicular-simple-one.cc'

#     obj = bld.create_ns3_program('vehicular-simple-two', ['millicar','core', 'propagation', 'spectrum', 'mmwave'])
#     obj.source = 'vehicular-simple-two.cc'

#     obj = bld.create_ns3_program('vehicular-simple-three', ['millicar','core', 'propagation', 'spectrum', 'mmwave'])
#     obj.source = 'vehicular-simple-three.cc'

#     obj = bld.create_ns3_program('vehicular-simple-four', ['millicar','core', 'propagation', 'spectrum', 'mmwave'])
#     obj.source = 'vehicular-simple-four.cc'

#     obj = bld.create_ns3_program('mmwave-vehicular-link-adaptation-example', ['millicar'])
#     obj.source = 'mmwave-vehicular-link-adaptation-example.cc'



build_lib_example(
  NAME avehicular-simple-one # example named aodv
  SOURCE_FILES vehicular-simple-one.cc # single source file aodv.cc
  LIBRARIES_TO_LINK # depends on wifi, internet, aodv and internet-apps
    ${libmillicar}
    ${libcore}
    ${libpropagation}
    ${libspectrum}
    ${libmmwave}
)

build_lib_example(
  NAME avehicular-simple-two # example named aodv
  SOURCE_FILES vehicular-simple-two.cc # single source file aodv.cc
  LIBRARIES_TO_LINK # depends on wifi, internet, aodv and internet-apps
    ${libmillicar}
    ${libcore}
    ${libpropagation}
    ${libspectrum}
    ${libmmwave}
)

build_lib_example(
  NAME avehicular-simple-three # example named aodv
  SOURCE_FILES vehicular-simple-three.cc # single source file aodv.cc
  LIBRARIES_TO_LINK # depends on wifi, internet, aodv and internet-apps
    ${libmillicar}
    ${libcore}
    ${libpropagation}
    ${libspectrum}
    ${libmmwave}
)

build_lib_example(
  NAME avehicular-simple-four # example named aodv
  SOURCE_FILES vehicular-simple-four.cc # single source file aodv.cc
  LIBRARIES_TO_LINK # depends on wifi, internet, aodv and internet-apps
    ${libmillicar}
    ${libcore}
    ${libpropagation}
    ${libspectrum}
    ${libmmwave}
)

build_lib_example(
  NAME mmwave-vehicular-link-adaptation-example # example named aodv
  SOURCE_FILES mmwave-vehicular-link-adaptation-example.cc # single source file aodv.cc
  LIBRARIES_TO_LINK # depends on wifi, internet, aodv and internet-apps
    ${libmillicar}
)