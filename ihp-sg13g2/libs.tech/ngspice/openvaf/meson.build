
openvaf         = find_program( 'openvaf' )
psp103_nqs_va   = files( 'psp103_nqs.va' )
psp103_nqs_osdi = 'psp103_nqs.osdi'

psp103_nqs = custom_target( 'psp103_nqs'
                          , output:      psp103_nqs_osdi
                          , input:       psp103_nqs_va
                          , command:     [ openvaf, '@INPUT@', '-o', '@OUTPUT@' ]
                          , install:     true
                          , install_dir: pdks_dir / 'libs.tech' / 'ngspice' / 'openvaf'
                          )
