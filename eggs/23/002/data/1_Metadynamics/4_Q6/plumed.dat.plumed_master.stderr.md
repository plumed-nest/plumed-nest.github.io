**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[fv-az1344-582:63109] *** Process received signal ***
[fv-az1344-582:63109] Signal: Aborted (6)
[fv-az1344-582:63109] Signal code:  (-6)
[fv-az1344-582:63109] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f187c645330]
[fv-az1344-582:63109] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f187c69eb2c]
[fv-az1344-582:63109] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f187c64527e]
[fv-az1344-582:63109] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f187c6288ff]
[fv-az1344-582:63109] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f187caa5ff5]
[fv-az1344-582:63109] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f187cabb0da]
[fv-az1344-582:63109] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f187caa5a55]
[fv-az1344-582:63109] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f187caa5a6f]
[fv-az1344-582:63109] [ 8] plumed_master(+0x146dd)[0x55f65bed66dd]
[fv-az1344-582:63109] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f187c62a1ca]
[fv-az1344-582:63109] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f187c62a28b]
[fv-az1344-582:63109] [11] plumed_master(+0x15365)[0x55f65bed7365]
[fv-az1344-582:63109] *** End of error message ***
</pre>
{% endraw %}
