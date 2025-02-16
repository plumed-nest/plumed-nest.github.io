**Project ID:** [plumID:25.006]({{ '/' | absolute_url }}eggs/25/006/)  
Stderr for source:  PROTACs_PBMetaD_PLUMED-NEST/Input_Files/plumed_lastbias.dat   
Download: [zipped raw stdout](plumed_lastbias.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_lastbias.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label d_tbut_ph_brd4 : could not find file named ../colvar_distances.data
[fv-az1781-845:60169] *** Process received signal ***
[fv-az1781-845:60169] Signal: Aborted (6)
[fv-az1781-845:60169] Signal code:  (-6)
[fv-az1781-845:60169] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2530845330]
[fv-az1781-845:60169] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f253089eb2c]
[fv-az1781-845:60169] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f253084527e]
[fv-az1781-845:60169] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f25308288ff]
[fv-az1781-845:60169] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2530ca5ff5]
[fv-az1781-845:60169] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2530cbb0da]
[fv-az1781-845:60169] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2530ca5a55]
[fv-az1781-845:60169] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2530ca5a6f]
[fv-az1781-845:60169] [ 8] plumed(+0x146dd)[0x55a9e6bfe6dd]
[fv-az1781-845:60169] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f253082a1ca]
[fv-az1781-845:60169] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f253082a28b]
[fv-az1781-845:60169] [11] plumed(+0x15365)[0x55a9e6bff365]
[fv-az1781-845:60169] *** End of error message ***
</pre>
{% endraw %}
