**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az2209-645:61666] *** Process received signal ***
[fv-az2209-645:61666] Signal: Aborted (6)
[fv-az2209-645:61666] Signal code:  (-6)
[fv-az2209-645:61666] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d5a245330]
[fv-az2209-645:61666] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d5a29eb2c]
[fv-az2209-645:61666] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d5a24527e]
[fv-az2209-645:61666] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d5a2288ff]
[fv-az2209-645:61666] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d5a6a5ff5]
[fv-az2209-645:61666] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d5a6bb0da]
[fv-az2209-645:61666] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d5a6a5a55]
[fv-az2209-645:61666] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d5a6a5a6f]
[fv-az2209-645:61666] [ 8] plumed(+0x146dd)[0x56280cb3d6dd]
[fv-az2209-645:61666] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d5a22a1ca]
[fv-az2209-645:61666] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d5a22a28b]
[fv-az2209-645:61666] [11] plumed(+0x15365)[0x56280cb3e365]
[fv-az2209-645:61666] *** End of error message ***
</pre>
{% endraw %}
