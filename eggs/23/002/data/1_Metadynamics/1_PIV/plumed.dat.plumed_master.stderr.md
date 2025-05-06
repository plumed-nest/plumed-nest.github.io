**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az2209-645:61577] *** Process received signal ***
[fv-az2209-645:61577] Signal: Aborted (6)
[fv-az2209-645:61577] Signal code:  (-6)
[fv-az2209-645:61577] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe101e45330]
[fv-az2209-645:61577] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe101e9eb2c]
[fv-az2209-645:61577] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe101e4527e]
[fv-az2209-645:61577] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe101e288ff]
[fv-az2209-645:61577] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe1022a5ff5]
[fv-az2209-645:61577] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe1022bb0da]
[fv-az2209-645:61577] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe1022a5a55]
[fv-az2209-645:61577] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe1022a5a6f]
[fv-az2209-645:61577] [ 8] plumed_master(+0x146dd)[0x55c75f6e06dd]
[fv-az2209-645:61577] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe101e2a1ca]
[fv-az2209-645:61577] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe101e2a28b]
[fv-az2209-645:61577] [11] plumed_master(+0x15365)[0x55c75f6e1365]
[fv-az2209-645:61577] *** End of error message ***
</pre>
{% endraw %}
