**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az2209-645:61631] *** Process received signal ***
[fv-az2209-645:61631] Signal: Aborted (6)
[fv-az2209-645:61631] Signal code:  (-6)
[fv-az2209-645:61631] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcc2dc45330]
[fv-az2209-645:61631] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcc2dc9eb2c]
[fv-az2209-645:61631] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcc2dc4527e]
[fv-az2209-645:61631] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcc2dc288ff]
[fv-az2209-645:61631] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcc2e0a5ff5]
[fv-az2209-645:61631] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcc2e0bb0da]
[fv-az2209-645:61631] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcc2e0a5a55]
[fv-az2209-645:61631] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcc2e0a5a6f]
[fv-az2209-645:61631] [ 8] plumed_master(+0x146dd)[0x56361df456dd]
[fv-az2209-645:61631] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcc2dc2a1ca]
[fv-az2209-645:61631] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcc2dc2a28b]
[fv-az2209-645:61631] [11] plumed_master(+0x15365)[0x56361df46365]
[fv-az2209-645:61631] *** End of error message ***
</pre>
{% endraw %}
