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
[fv-az1390-170:05357] *** Process received signal ***
[fv-az1390-170:05357] Signal: Aborted (6)
[fv-az1390-170:05357] Signal code:  (-6)
[fv-az1390-170:05357] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec1a645330]
[fv-az1390-170:05357] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec1a69eb2c]
[fv-az1390-170:05357] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec1a64527e]
[fv-az1390-170:05357] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec1a6288ff]
[fv-az1390-170:05357] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec1aaa5ff5]
[fv-az1390-170:05357] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec1aabb0da]
[fv-az1390-170:05357] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec1aaa5a55]
[fv-az1390-170:05357] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec1aaa5a6f]
[fv-az1390-170:05357] [ 8] plumed(+0x146dd)[0x556ffe5e76dd]
[fv-az1390-170:05357] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec1a62a1ca]
[fv-az1390-170:05357] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec1a62a28b]
[fv-az1390-170:05357] [11] plumed(+0x15365)[0x556ffe5e8365]
[fv-az1390-170:05357] *** End of error message ***
</pre>
{% endraw %}
