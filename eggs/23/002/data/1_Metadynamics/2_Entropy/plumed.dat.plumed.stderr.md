**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az2209-645:61615] *** Process received signal ***
[fv-az2209-645:61615] Signal: Aborted (6)
[fv-az2209-645:61615] Signal code:  (-6)
[fv-az2209-645:61615] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f80b5a45330]
[fv-az2209-645:61615] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f80b5a9eb2c]
[fv-az2209-645:61615] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f80b5a4527e]
[fv-az2209-645:61615] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f80b5a288ff]
[fv-az2209-645:61615] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f80b5ea5ff5]
[fv-az2209-645:61615] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f80b5ebb0da]
[fv-az2209-645:61615] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f80b5ea5a55]
[fv-az2209-645:61615] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f80b5ea5a6f]
[fv-az2209-645:61615] [ 8] plumed(+0x146dd)[0x5580e2bbd6dd]
[fv-az2209-645:61615] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f80b5a2a1ca]
[fv-az2209-645:61615] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f80b5a2a28b]
[fv-az2209-645:61615] [11] plumed(+0x15365)[0x5580e2bbe365]
[fv-az2209-645:61615] *** End of error message ***
</pre>
{% endraw %}
