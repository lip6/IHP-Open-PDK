
project(
  'ihpsg13g2-pdk',
   version:  '2024.10.15',
   meson_version: '>= 1.2.0',
)

py       = import( 'python' ).find_installation( pure:false )
py_deps  = dependency( 'python3', required: true )
pdks_dir = py.get_install_dir() / 'pdks' / 'ihpsg13g2'

install_subdir( 'libs.ref' , install_dir:pdks_dir )
install_subdir( 'libs.tech', install_dir:pdks_dir )

