**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_map_to_reference_map.dat   
Download: [zipped raw stdout](plumed_map_to_reference_map.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_map_to_reference_map.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: SKETCHMAP_PROJECTION LABEL=smap ARG=d1,d2,d3,d4,d5,d6,d7,d8,d9,d10,d11,d12,d13,d14,d15,d16,d17,d18,d19,d20,d21,d22,d23,d24,d25,d26,d27,d28,d29,d30,d31,d32,d33,d34,d35,d36,d37,d38,d39,d40,d41,d42,d43,d44,d45,d46,d47,d48,d49,d50,d51 REFERENCE=ref_data.pdb PROPERTY=smap_coord-1,smap_coord-2 WEIGHT=lwe HIGH_DIM_FUNCTION=SMAP R_0=1.5 A=2 B=2 LOW_DIM_FUNCTION=SMAP R_0=1.5 A=2 B=2 CGTOL=1E-3
Maybe a missing space or a typo?
[fv-az1272-890:68109] *** Process received signal ***
[fv-az1272-890:68109] Signal: Aborted (6)
[fv-az1272-890:68109] Signal code:  (-6)
[fv-az1272-890:68109] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd3dbc42520]
[fv-az1272-890:68109] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd3dbc969fc]
[fv-az1272-890:68109] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd3dbc42476]
[fv-az1272-890:68109] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd3dbc287f3]
[fv-az1272-890:68109] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fd3dc0a4f26]
[fv-az1272-890:68109] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fd3dc0b6d9c]
[fv-az1272-890:68109] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fd3dc0b6e07]
[fv-az1272-890:68109] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd3dc0b70bb]
[fv-az1272-890:68109] [ 8] plumed_master(+0x12e7f)[0x56073979ee7f]
[fv-az1272-890:68109] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd3dbc29d90]
[fv-az1272-890:68109] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd3dbc29e40]
[fv-az1272-890:68109] [11] plumed_master(+0x13115)[0x56073979f115]
[fv-az1272-890:68109] *** End of error message ***
</pre>
{% endraw %}
