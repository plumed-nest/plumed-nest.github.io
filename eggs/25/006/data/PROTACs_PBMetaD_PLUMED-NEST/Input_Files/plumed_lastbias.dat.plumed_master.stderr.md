**Project ID:** [plumID:25.006]({{ '/' | absolute_url }}eggs/25/006/)  
Stderr for source:  PROTACs_PBMetaD_PLUMED-NEST/Input_Files/plumed_lastbias.dat   
Download: [zipped raw stdout](plumed_lastbias.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lastbias.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label d_tbut_ph_brd4 : could not find file named ../colvar_distances.data
[fv-az1390-170:05372] *** Process received signal ***
[fv-az1390-170:05372] Signal: Aborted (6)
[fv-az1390-170:05372] Signal code:  (-6)
[fv-az1390-170:05372] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9f65e45330]
[fv-az1390-170:05372] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9f65e9eb2c]
[fv-az1390-170:05372] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9f65e4527e]
[fv-az1390-170:05372] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9f65e288ff]
[fv-az1390-170:05372] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9f662a5ff5]
[fv-az1390-170:05372] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9f662bb0da]
[fv-az1390-170:05372] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9f662a5a55]
[fv-az1390-170:05372] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9f662a5a6f]
[fv-az1390-170:05372] [ 8] plumed_master(+0x146dd)[0x55feacf256dd]
[fv-az1390-170:05372] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9f65e2a1ca]
[fv-az1390-170:05372] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9f65e2a28b]
[fv-az1390-170:05372] [11] plumed_master(+0x15365)[0x55feacf26365]
[fv-az1390-170:05372] *** End of error message ***
</pre>
{% endraw %}
