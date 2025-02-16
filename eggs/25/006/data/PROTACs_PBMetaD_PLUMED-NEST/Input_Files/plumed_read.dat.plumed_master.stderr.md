**Project ID:** [plumID:25.006]({{ '/' | absolute_url }}eggs/25/006/)  
Stderr for source:  PROTACs_PBMetaD_PLUMED-NEST/Input_Files/plumed_read.dat   
Download: [zipped raw stdout](plumed_read.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_read.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label d_tbut_ph_brd4 : could not find file named ../colvar_distances.data
[fv-az1781-845:60294] *** Process received signal ***
[fv-az1781-845:60294] Signal: Aborted (6)
[fv-az1781-845:60294] Signal code:  (-6)
[fv-az1781-845:60294] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3ff7045330]
[fv-az1781-845:60294] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3ff709eb2c]
[fv-az1781-845:60294] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3ff704527e]
[fv-az1781-845:60294] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3ff70288ff]
[fv-az1781-845:60294] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3ff74a5ff5]
[fv-az1781-845:60294] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3ff74bb0da]
[fv-az1781-845:60294] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3ff74a5a55]
[fv-az1781-845:60294] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3ff74a5a6f]
[fv-az1781-845:60294] [ 8] plumed_master(+0x146dd)[0x558434b1e6dd]
[fv-az1781-845:60294] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3ff702a1ca]
[fv-az1781-845:60294] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3ff702a28b]
[fv-az1781-845:60294] [11] plumed_master(+0x15365)[0x558434b1f365]
[fv-az1781-845:60294] *** End of error message ***
</pre>
{% endraw %}
